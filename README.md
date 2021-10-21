# Rpeds
Mon discord https://discord.gg/Z6UPEvA628

######################################################

######## Pour Ajouter un Peds dans le menu ########

Rajouter dans le client
#######################

RageUI.Button("Nom de ton perso", "Pour se mettre Nom de ton perso", {RightLabel = ""}, true, function(Hovered, Active, Selected)
                if (Selected) then   
                local j1 = PlayerId()
    			local p1 = GetHashKey('Le nom du ped')
    			RequestModel(p1)
    			while not HasModelLoaded(p1) do
      			  Wait(100)
   				 end
   				 SetPlayerModel(j1, p1)
   				 SetModelAsNoLongerNeeded(p1)
   				 ESX.ShowNotification('Tu est maintenant en Nom de ton perso')
                end      
            
            end)

######## Pour pouvoir utiliser le Menu ########

Merci de bien vouloir mettre votre steam id dans le server.lua

Les Starts 
#############################

ensure K_peds

#############

ensure homer
ensure shrek 
ensure MickeyMouse
