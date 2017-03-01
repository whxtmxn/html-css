# html-css
Apprentissage html css
Le Html et le CSS :

# Définition générales html :
## Dans index01.html :  

```html  

<!DOCTYPE Html>
<html>
  <head>

  </head>

  <body>

  </body>

</html>

```
### ! Indentation :
Manière de structurer les choses pour nous permettre de clarifier son travail.
* nécessaire pour le travail à plusieurs
* Permet de se repérer plus facilement dans la hiérarchie


### Head  / Métadonnées :
informations en arrière plan.
Informations fonctionnelles de la page
``` html
* Titre → <title>
* Type de caractères →  <meta charset=”utf-8”>
* Feuilles de styles →     <link rel="stylesheet" href="/css/style.css">
* Frameworks → <link> / <script>
```

### Body :
Contenu visible du site
### Header :
 Informations de fonctionnement relatives au site (menu, barre de recherche, Log in, logo ou nom du site)
### Footer :
Bas de page (coordonnées, navigation secondaire, etc…)

### Div :
Bloc d’éléments→ permet de manipuler un ensemble d'éléments.



### Les commentaires:
    	Les commentaires servent à noter des informations textuels au milieu du code sans perturber son exécution. Ils peuvent également servir à masquer une partie du code sans avoir à effacer son contenus.

	(raccourcis clavier : Ctrl + Maj + /)
``` html
* commentaires en html : < !--  Zone de commentaire -->  →
* commentaire en CSS : /*  Zone de commentaire   */
```
 #### Déplacer un paragraphe d’un emplacement à un autre:
 ctrl + flèche haut / bas.




# Définitions générales Css :

## Class :
Éléments central du html / css, les classes permettent de sélectionner plusieurs éléments et de leur appliquer du style dans l’ensemble.
On définit à travers les classes, des propriétés communes à plusieurs éléments.

## Id :
Identité de la balise, l’attribut ID permet d’identifier un balise précisément. Elle va nous permettre d’appliquer du style qui ne doit apparaître que sur cet élément.

## Typo / Font / Police de caractère :
	La police de caractère correspond à ce que l’on nomme en css la font-family.
Ce sont les visuels de caractère qui vont nous permettre de changer l’affichage du texte.

On peut les récupérer sur  google font ou Dafont et les charger via un système de balise
```html
 <link>
 ```
 ou directement dans le css via ce que l’on appel les media queries
