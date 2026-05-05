# NavigationDrawerDemo 

Ce projet est une application Android simple qui illustre comment mettre en place un **Navigation Drawer** (menu latéral) avec une navigation personnalisée entre plusieurs fragments.

##  Résumé du Projet

L'objectif était de transformer une activité de base en une interface moderne avec un tiroir de navigation fonctionnel permettant de basculer entre différents écrans dynamiquement.

### Étapes de réalisation :

1.  **Mise en place de la structure** : Utilisation du modèle *Navigation Drawer Activity* d'Android Studio pour générer les composants de base (DrawerLayout, NavigationView).
2.  **Personnalisation graphique** :
    *   Création d'icônes vectorielles pour chaque section (Home, Dashboard, List, Video).
    *   Modification du menu latéral dans `res/menu/activity_main_drawer.xml`.
3.  **Gestion des Fragments** :
    *   Création de fragments simples (`BlankFragment`, `BlankFragment2`, `VideoFragment`) avec des couleurs de fond distinctes.
    *   Implémentation d'un `ListFragment` (`FragmentList`) pour afficher une liste d'éléments prédéfinis.
4.  **Navigation Manuelle** :
    *   Remplacement du NavHost par un `FrameLayout` dans `content_main.xml`.
    *   Utilisation du `FragmentManager` dans `MainActivity.java` pour remplacer le contenu au clic sur le menu.
5.  **Interactivité** : Ajout d'un `ActionBarDrawerToggle` pour synchroniser l'icône "hamburger" et gestion du bouton retour.

## Demonstration
![video](https://github.com/user-attachments/assets/af0f1a2a-6e73-4cfb-b90f-ce748f278129)
