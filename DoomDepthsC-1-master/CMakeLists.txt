cmake_minimum_required(VERSION 3.26)
project(DoomDepthsC_1_master C)

set(CMAKE_C_STANDARD 11)

include_directories(DoomDepthsC-1-master/carte)
include_directories(DoomDepthsC-1-master/combat)
include_directories(DoomDepthsC-1-master/equipement)
include_directories(DoomDepthsC-1-master/Joueur)
include_directories(DoomDepthsC-1-master/Monstre)
include_directories(DoomDepthsC-1-master/sauvegarde)

add_executable(DoomDepthsC_1_master
        DoomDepthsC-1-master/carte/carte.c
        DoomDepthsC-1-master/carte/carte.h
        DoomDepthsC-1-master/carte/listeCarte.h
        DoomDepthsC-1-master/combat/combat.c
        DoomDepthsC-1-master/combat/combat.h
        DoomDepthsC-1-master/equipement/arme.c
        DoomDepthsC-1-master/equipement/arme.h
        DoomDepthsC-1-master/equipement/armure.c
        DoomDepthsC-1-master/equipement/armure.h
        DoomDepthsC-1-master/equipement/listeArme.h
        DoomDepthsC-1-master/equipement/listeArmure.h
        DoomDepthsC-1-master/Joueur/joueur.c
        DoomDepthsC-1-master/Joueur/joueur.h
        DoomDepthsC-1-master/Monstre/generation.c
        DoomDepthsC-1-master/Monstre/listeBoss.h
        DoomDepthsC-1-master/Monstre/monstre.h
        DoomDepthsC-1-master/sauvegarde/sauvegarde.c
        DoomDepthsC-1-master/sauvegarde/sauvegarde.h
        DoomDepthsC-1-master/main.c
        DoomDepthsC-1-master/Sorts/sorts.c
        DoomDepthsC-1-master/Sorts/sorts.h)
