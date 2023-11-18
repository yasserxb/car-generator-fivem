import os


nom_dossier = (input("quelle est le nom du dossier : "))
nom_voiture = (input("quelle est le nom de la voiture : "))

try:
    os.makedirs(nom_dossier)
    os.chdir(nom_dossier)

    with open("vehicles.meta","w+") as file:
        file.write("""
        <?xml version="1.0" encoding="UTF-8"?>
        <CVehicleModelInfo__InitDataList>
        <residentTxd>vehshare</residentTxd>
        <residentAnims />
        <InitDatas>
            <Item>
      <modelName>{}</modelName>
      <txdName>{}</txdName>
      <handlingId>{}</handlingId>
      <gameName>{}GT18</gameName>
      <vehicleMakeName>AUDI</vehicleMakeName>
      <expressionDictName>null</expressionDictName>
      <expressionName>null</expressionName>
      <animConvRoofDictName>null</animConvRoofDictName>
      <animConvRoofName>null</animConvRoofName>
      <animConvRoofWindowsAffected />
      <ptfxAssetName>null</ptfxAssetName>
      <audioNameHash>KHAMELION</audioNameHash>
      <layout>LAYOUT_STD_HIGHWINDOW</layout>
      <coverBoundOffsets>SCHAFTER_COVER_OFFSET_INFO</coverBoundOffsets>
      <explosionInfo>EXPLOSION_INFO_DEFAULT</explosionInfo>
      <scenarioLayout />
      <cameraName>DEFAULT_FOLLOW_VEHICLE_CAMERA</cameraName>
      <aimCameraName>DEFAULT_THIRD_PERSON_VEHICLE_AIM_CAMERA</aimCameraName>
      <bonnetCameraName>VEHICLE_BONNET_CAMERA_STANDARD_LONG</bonnetCameraName>
      <povCameraName>DEFAULT_POV_CAMERA_LOOKAROUND_MID</povCameraName>
      <FirstPersonDriveByIKOffset x="0.000000" y="-0.055000" z="0.000000" />
      <FirstPersonDriveByUnarmedIKOffset x="0.000000" y="-0.025000" z="0.000000" />
	  <FirstPersonProjectileDriveByIKOffset x="0.000000" y="-0.120000" z="0.030000" />
	  <FirstPersonProjectileDriveByPassengerIKOffset x="0.000000" y="0.030000" z="-0.040000" />
	  <FirstPersonProjectileDriveByRearLeftIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByRearRightIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerIKOffset x="0.000000" y="-0.055000" z="0.020000" />
	  <FirstPersonDriveByRightRearPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerUnarmedIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerUnarmedIKOffset x="0.000000" y="-0.035000" z="0.000000" />
	  <FirstPersonMobilePhoneOffset x="0.133000" y="0.228000" z="0.468000" />
      <FirstPersonPassengerMobilePhoneOffset x="0.136000" y="0.223000" z="0.425000" />
      <PovCameraOffset x="0.0000000" y="-0.250000" z="0.600000" />
      <PovCameraVerticalAdjustmentForRollCage value="0.000000" />
      <PovPassengerCameraOffset x="0.000000" y="0.000000" z="0.070000" />
      <PovRearPassengerCameraOffset x="0.000000" y="0.000000" z="0.150000" />
      <vfxInfoName>VFXVEHICLEINFO_CAR_GENERIC</vfxInfoName>
      <shouldUseCinematicViewMode value="true" />
      <shouldCameraTransitionOnClimbUpDown value="false" />
      <shouldCameraIgnoreExiting value="false" />
      <AllowPretendOccupants value="true" />
      <AllowJoyriding value="true" />
      <AllowSundayDriving value="true" />
      <AllowBodyColorMapping value="true" />
      <wheelScale value="0.279400" />
      <wheelScaleRear value="0.279400" />
      <dirtLevelMin value="0.000000" />
      <dirtLevelMax value="0.700000" />
      <envEffScaleMin value="0.000000" />
      <envEffScaleMax value="1.000000" />
      <envEffScaleMin2 value="0.000000" />
      <envEffScaleMax2 value="1.000000" />
      <damageMapScale value="0.600000" />
      <damageOffsetScale value="1.000000" />
      <diffuseTint value="0x00FFFFFF" />
      <steerWheelMult value="1.000000" />
      <HDTextureDist value="5.000000" />
      <lodDistances content="float_array">
        500.000000
        500.000000
        500.000000
        500.000000
        500.000000
        500.000000
      </lodDistances>
      <minSeatHeight value="0.85" />
      <identicalModelSpawnDistance value="20" />
      <maxNumOfSameColor value="10" />
      <defaultBodyHealth value="1000.000000" />
      <pretendOccupantsScale value="1.000000" />
      <visibleSpawnDistScale value="1.000000" />
      <trackerPathWidth value="2.000000" />
      <weaponForceMult value="1.000000" />
      <frequency value="90" />
      <swankness>SWANKNESS_2</swankness>
      <maxNum value="20" />
      <flags>FLAG_IS_ELECTRIC FLAG_SPAWN_ON_TRAILER FLAG_AVERAGE_CAR FLAG_HAS_EXTRAS FLAG_USE_FULL_ANIMS_FOR_MP_WARP_ENTRY_POINTS FLAG_PARKING_SENSORS FLAG_ATTACH_TRAILER_IN_CITY FLAG_ATTACH_TRAILER_ON_HIGHWAY FLAG_SPAWN_BOAT_ON_TRAILER</flags>
      <type>VEHICLE_TYPE_CAR</type>
      <plateType>VPT_FRONT_AND_BACK_PLATES</plateType>
      <dashboardType>VDT_RACE</dashboardType>
      <vehicleClass>VC_COUPE</vehicleClass>
      <wheelType>VWT_SPORT</wheelType>
      <trailers>
        <Item>boattrailer</Item>
        <Item>trailersmall</Item>
        <Item>trailersmall2</Item>
        <Item>cotrailer</Item>
        <Item>caratrail</Item>
	<Item>20fttrailer</Item>
	<Item>foxtr1</Item>
      </trailers>
      <additionalTrailers>
        <Item>boattrailer</Item>
        <Item>trailersmall</Item>
        <Item>trailersmall2</Item>
        <Item>cotrailer</Item>
        <Item>caratrail</Item>
	<Item>20fttrailer</Item>
	<Item>foxtr1</Item>
      </additionalTrailers>
      <drivers />
      <extraIncludes />
      <doorsWithCollisionWhenClosed />
      <driveableDoors />
      <bumpersNeedToCollideWithMap value="false" />
      <needsRopeTexture value="false" />
      <requiredExtras>EXTRA_1 EXTRA_2</requiredExtras>
      <rewards />
      <cinematicPartCamera>
        <Item>WHEEL_FRONT_RIGHT_CAMERA</Item>
        <Item>WHEEL_FRONT_LEFT_CAMERA</Item>
        <Item>WHEEL_REAR_RIGHT_CAMERA</Item>
        <Item>WHEEL_REAR_LEFT_CAMERA</Item>
      </cinematicPartCamera>
      <NmBraceOverrideSet />
      <buoyancySphereOffset x="0.000000" y="0.000000" z="0.000000" />
      <buoyancySphereSizeScale value="1.000000" />
      <pOverrideRagdollThreshold type="NULL" />
	  <firstPersonDrivebyData>	
      </firstPersonDrivebyData>
    </Item>
  </InitDatas>
  <txdRelationships>
    <Item>
      <parent>vehicles_dom_interior</parent>
      <child>{}</child>
    </Item>
  </txdRelationships>
</CVehicleModelInfo__InitDataList>
        """.format(nom_voiture,nom_voiture,nom_voiture,nom_voiture,nom_voiture))
        file.close()
    with open("carcols.meta","w+") as file:
        file.write("""<?xml version="1.0" encoding="UTF-8"?>

<CVehicleModelInfoVarGlobal>
  <Kits>
    <Item>
      <kitName>896_{}_modkit</kitName>
      <id value="896" />
      <kitType>MKT_SPECIAL</kitType>
      <visibleMods>
	<Item>
          <modelName>ocn{}_roof_1</modelName>
          <modShopLabel>SOLAR_ROOF</modShopLabel>
          <linkedModels />
          <turnOffBones>
		<Item>misc_m</Item>
		<Item>misc_l</Item>
          </turnOffBones>
          <type>VMT_ROOF</type>
          <bone>chassis</bone>
          <collisionBone>chassis</collisionBone>
          <cameraPos>VMCP_DEFAULT</cameraPos>
          <audioApply value="1.000000" />
          <weight value="0" />
          <turnOffExtra value="false" />
          <disableBonnetCamera value="false" />
          <allowBonnetSlide value="true" />
        </Item>
	<Item>
          <modelName>ocn{}_grille_1</modelName>
          <modShopLabel>PAINTED_GRILL</modShopLabel>
          <linkedModels />
          <turnOffBones>
		<Item>misc_c</Item>
          </turnOffBones>
          <type>VMT_GRILL</type>
          <bone>chassis</bone>
          <collisionBone>chassis</collisionBone>
          <cameraPos>VMCP_DEFAULT</cameraPos>
          <audioApply value="1.000000" />
          <weight value="0" />
          <turnOffExtra value="false" />
          <disableBonnetCamera value="false" />
          <allowBonnetSlide value="true" />
        </Item>
      </visibleMods>
      <linkMods>
      </linkMods>
      <statMods>
        <Item>
          <identifier />
          <modifier value="25" />
          <audioApply value="1.000000" />
          <weight value="20" />
          <type>VMT_ENGINE</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="50" />
          <audioApply value="1.000000" />
          <weight value="20" />
          <type>VMT_ENGINE</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="75" />
          <audioApply value="1.000000" />
          <weight value="20" />
          <type>VMT_ENGINE</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="100" />
          <audioApply value="1.000000" />
          <weight value="20" />
          <type>VMT_ENGINE</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="25" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_BRAKES</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="50" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_BRAKES</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="100" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_BRAKES</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="25" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_GEARBOX</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="50" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_GEARBOX</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="100" />
          <audioApply value="1.000000" />
          <weight value="5" />
          <type>VMT_GEARBOX</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="20" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_ARMOUR</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="40" />
          <audioApply value="1.000000" />
          <weight value="10" />
          <type>VMT_ARMOUR</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="60" />
          <audioApply value="1.000000" />
          <weight value="20" />
          <type>VMT_ARMOUR</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="80" />
          <audioApply value="1.000000" />
          <weight value="30" />
          <type>VMT_ARMOUR</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="100" />
          <audioApply value="1.000000" />
          <weight value="40" />
          <type>VMT_ARMOUR</type>
        </Item>
        <Item>
          <identifier>HORN_TRUCK</identifier>
          <modifier value="1766676233" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_COP</identifier>
          <modifier value="2904189469" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_CLOWN</identifier>
          <modifier value="2543206147" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_MUSICAL_1</identifier>
          <modifier value="1732399718" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_MUSICAL_2</identifier>
          <modifier value="2046162893" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_MUSICAL_3</identifier>
          <modifier value="2194999691" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_MUSICAL_4</identifier>
          <modifier value="2508304100" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HORN_MUSICAL_5</identifier>
          <modifier value="3707223535" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
		    <Item>
          <identifier>HORN_SAD_TROMBONE</identifier>
          <modifier value="632950117" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_1</identifier>
          <modifier value="3628534289" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_2</identifier>
          <modifier value="3892554122" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_3</identifier>
          <modifier value="4112892878" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_4</identifier>
          <modifier value="116877169" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_5</identifier>
          <modifier value="2684983719" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>MUSICAL_HORN_BUSINESS_6</identifier>
          <modifier value="2982690084" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>MUSICAL_HORN_BUSINESS_7</identifier>
          <modifier value="3203290992" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_C0</identifier>
          <modifier value="771284519" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_D0</identifier>
          <modifier value="2586621229" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_E0</identifier>
          <modifier value="283386134" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_F0</identifier>
          <modifier value="3884502400" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_G0</identifier>
          <modifier value="265723083" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_A0</identifier>
          <modifier value="1746883687" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_B0</identifier>
          <modifier value="1919870950" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
    		</Item>
    		<Item>
          <identifier>DLC_BUSI2_C_MAJOR_NOTES_C1</identifier>
          <modifier value="1085277077" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
		    </Item>
        <Item>
          <identifier>HIPSTER_HORN_1</identifier>
          <modifier value="444549672" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HIPSTER_HORN_2</identifier>
          <modifier value="1603064898" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HIPSTER_HORN_3</identifier>
          <modifier value="240366033" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>HIPSTER_HORN_4</identifier>
          <modifier value="960137118" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>INDEP_HORN_1</identifier>
          <modifier value="3572144790" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>INDEP_HORN_2</identifier>
          <modifier value="3801396714" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>INDEP_HORN_3</identifier>
          <modifier value="2843657151" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
        </Item>
        <Item>
          <identifier>INDEP_HORN_4</identifier>
          <modifier value="3341811489" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_HORN</type>
       </Item>
       <Item>
          <identifier />
          <modifier value="5" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_SUSPENSION</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="10" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_SUSPENSION</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="15" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_SUSPENSION</type>
        </Item>
        <Item>
          <identifier />
          <modifier value="20" />
          <audioApply value="1.000000" />
          <weight value="0" />
          <type>VMT_SUSPENSION</type>
        </Item>
      </statMods>
      <slotNames>
	  </slotNames>
      <liveryNames />
    </Item>
   </Kits>
   <Lights>
    <Item>
      
      <id value="9955" />	
      <indicator>
        <intensity value="0.375000" />
        <falloffMax value="2.500000" />
        <falloffExponent value="8.000000" />
        <innerConeAngle value="30.000000" />
        <outerConeAngle value="80.000000" />
        <emmissiveBoost value="false" />
        <color value="0xFFFF8000" />
      </indicator>
      <rearIndicatorCorona>
        <size value="0.000000" />
        <size_far value="0.000000" />
        <intensity value="0.000000" />
        <intensity_far value="0.000000" />
        <color value="0x00000000" />
        <numCoronas value="1" />
        <distBetweenCoronas value="128" />
        <distBetweenCoronas_far value="255" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.250000" />
        <pullCoronaIn value="false" />
      </rearIndicatorCorona>
      <frontIndicatorCorona>
        <size value="0.000000" />
        <size_far value="0.000000" />
        <intensity value="0.000000" />
        <intensity_far value="0.000000" />
        <color value="0x00000000" />
        <numCoronas value="1" />
        <distBetweenCoronas value="128" />
        <distBetweenCoronas_far value="255" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.250000" />
        <pullCoronaIn value="false" />
      </frontIndicatorCorona>
      <tailLight>
        <intensity value="0.250000" />
        <falloffMax value="4.000000" />
        <falloffExponent value="16.000000" />
        <innerConeAngle value="45.000000" />
        <outerConeAngle value="90.000000" />
        <emmissiveBoost value="false" />
        <color value="0xFFFF0000" />
      </tailLight>
      <tailLightCorona>
        <size value="0.900000" />
        <size_far value="5.300000" />
        <intensity value="4.000000" />
        <intensity_far value="1.000000" />
        <color value="0xFFFF0E05" />
        <numCoronas value="0" />
        <distBetweenCoronas value="22" />
        <distBetweenCoronas_far value="255" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.000000" />
        <pullCoronaIn value="false" />
      </tailLightCorona>
      <tailLightMiddleCorona>
        <size value="0.100000" />
        <size_far value="0.500000" />
        <intensity value="0.100000" />
        <intensity_far value="0.200000" />
        <color value="0x88FF0000" />
        <numCoronas value="0" />
        <distBetweenCoronas value="65" />
        <distBetweenCoronas_far value="25" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.000000" />
        <pullCoronaIn value="false" />
      </tailLightMiddleCorona>
      <headLight>
        <intensity value="1.000000" />
        <falloffMax value="35.000000" />
        <falloffExponent value="16.000000" />
        <innerConeAngle value="0.000000" />
        <outerConeAngle value="60.209999" />
        <emmissiveBoost value="false" />
        <color value="0xFFFFFFCC" />
        <textureName>VehicleLight_car_standartmodern</textureName>
        <mirrorTexture value="true" />
      </headLight>
      <headLightCorona>
        <size value="0.080000" />
        <size_far value="1.000000" />
        <intensity value="5.000000" />
        <intensity_far value="1.000000" />
        <color value="0xFFFFFFFF" />
        <numCoronas value="0" />
        <distBetweenCoronas value="1" />
        <distBetweenCoronas_far value="255" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.000000" />
        <pullCoronaIn value="false" />
      </headLightCorona>
      <reversingLight>
        <intensity value="0.500000" />
        <falloffMax value="4.000000" />
        <falloffExponent value="32.000000" />
        <innerConeAngle value="45.000000" />
        <outerConeAngle value="90.000000" />
        <emmissiveBoost value="false" />
        <color value="0xFFFFFFFF" />
      </reversingLight>
      <reversingLightCorona>
        <size value="0.800000" />
        <size_far value="2.000000" />
        <intensity value="1.500000" />
        <intensity_far value="1.000000" />
        <color value="0x00F7F7F7" />
        <numCoronas value="0" />
        <distBetweenCoronas value="128" />
        <distBetweenCoronas_far value="255" />
        <xRotation value="0.000000" />
        <yRotation value="0.000000" />
        <zRotation value="0.000000" />
        <zBias value="0.250000" />
        <pullCoronaIn value="false" />
      </reversingLightCorona>
      <name>volv9019i</name>
    </Item>
    </Lights>
</CVehicleModelInfoVarGlobal>""".format(nom_voiture,nom_voiture,nom_voiture))
        file.close()
    with open("carvariations.meta","w+") as file:
        file.write("""<?xml version="1.0" encoding="UTF-8"?>

<CVehicleModelInfoVariation>
  <variationData> 
    <Item>
      <modelName>{}</modelName>
      <colors>
	<Item>
          <indices content="char_array">
            0
            27
            7
            0
            27
            1
          </indices>
          <liveries>
          </liveries>
        </Item>
	<Item>
          <indices content="char_array">
            4
            38
            134
            0
            38
            2
          </indices>
          <liveries>
          </liveries>
        </Item>
	<Item>
          <indices content="char_array">
            112
            70
            134
            0
            70
            117
          </indices>
          <liveries>
          </liveries>
        </Item>
      </colors>
      <kits>
        <Item>896_{}gt_modkit</Item>
      </kits>
      <windowsWithExposedEdges />
      <plateProbabilities>
        <Probabilities>
          <Item>
            <Name>Standard White</Name>
            <Value value="100" />
          </Item>
	</Probabilities>
      </plateProbabilities>
      <lightSettings value="9955" />
      <sirenSettings value="0" />
    </Item>
  </variationData>
</CVehicleModelInfoVariation>""".format(nom_voiture,nom_voiture))
        file.close()
    with open("handling.meta","w+") as file:
        file.write("""<?xml version="1.0" encoding="UTF-8"?>

<CHandlingDataMgr>
  <HandlingData>
      <Item type="CHandlingData">
      <handlingName>{}</handlingName>
      <fMass value="1500.000000" />
      <fInitialDragCoeff value="9.500000" />
      <fPercentSubmerged value="85.000000" />
      <vecCentreOfMassOffset x="0.000000" y="0.000000" z="-0.200000" />
      <vecInertiaMultiplier x="1.000000" y="1.200000" z="1.600000" />
      <fDriveBiasFront value="0.550000" />
      <nInitialDriveGears value="6" />
      <fInitialDriveForce value="0.420000" />
      <fDriveInertia value="1.000000" />
      <fClutchChangeRateScaleUpShift value="2.300000" />
      <fClutchChangeRateScaleDownShift value="2.300000" />
      <fInitialDriveMaxFlatVel value="198.000000" />
      <fBrakeForce value="0.450000" />
      <fBrakeBiasFront value="0.60000" />
      <fHandBrakeForce value="0.700000" />
      <fSteeringLock value="35.000000" />
      <fTractionCurveMax value="2.450000" />
      <fTractionCurveMin value="1.9750000" />
      <fTractionCurveLateral value="22.500000" />
      <fTractionSpringDeltaMax value="0.150000" />
      <fLowSpeedTractionLossMult value="1.300000" />
      <fCamberStiffnesss value="0.000000" />
      <fTractionBiasFront value="0.485000" />
      <fTractionLossMult value="0.000000" />
      <fSuspensionForce value="2.900000" />
      <fSuspensionCompDamp value="1.400000" />
      <fSuspensionReboundDamp value="2.500000" />
      <fSuspensionUpperLimit value="0.130000" />
      <fSuspensionLowerLimit value="-0.100000" />
      <fSuspensionRaise value="0.000000" />
      <fSuspensionBiasFront value="0.500000" />
      <fAntiRollBarForce value="0.35000" />
      <fAntiRollBarBiasFront value="0.5750000" />
      <fRollCentreHeightFront value="0.210000" />
      <fRollCentreHeightRear value="0.250000" />
      <fCollisionDamageMult value="0.700000" />
      <fWeaponDamageMult value="1.000000" />
      <fDeformationDamageMult value="0.700000" />
      <fEngineDamageMult value="1.500000" />
      <fPetrolTankVolume value="65.000000" />
      <fOilVolume value="5.000000" />
      <fSeatOffsetDistX value="0.000000" />
      <fSeatOffsetDistY value="-0.025000" />
      <fSeatOffsetDistZ value="0.050000" />
      <nMonetaryValue value="35000" />
      <strModelFlags>440010</strModelFlags>
      <strHandlingFlags>0</strHandlingFlags>
      <strDamageFlags>0</strDamageFlags>
      <AIHandling>AVERAGE</AIHandling>
      <SubHandlingData>
        <Item type="CCarHandlingData">
          <fBackEndPopUpCarImpulseMult value="0.100000" />
          <fBackEndPopUpBuildingImpulseMult value="0.030000" />
          <fBackEndPopUpMaxDeltaSpeed value="0.600000" />
        </Item>
        <Item type="NULL" />
        <Item type="NULL" />
      </SubHandlingData>
    </Item>
  </HandlingData>
</CHandlingDataMgr>
""".format(nom_voiture))
        file.close()
    with open("__resource.lua","w+") as file:
        file.write("""resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'
 author 'yasser212'
files {

    'handling.meta',
    'vehicles.meta',
    'carvariations.meta',
    'carcols.meta',

    
}

data_file 'HANDLING_FILE' 'handling.meta'
data_file 'VEHICLE_METADATA_FILE' 'vehicles.meta'
data_file 'CARCOLS_FILE' 'carcols.meta'
data_file 'VEHICLE_VARIATION_FILE' 'carvariations.meta'""")
        file.close()
    
    os.makedirs("stream")
except FileExistsError:
    print("dossier existe déja")
    pass

