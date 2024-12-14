# Titanic Dataset Analysis

Ce projet se concentre sur l'analyse du célèbre ensemble de données Titanic pour prédire la survie des passagers. En utilisant des techniques de machine learning, nous avons créé un modèle capable de prédire si un passager a survécu ou non en fonction de ses caractéristiques.

## Étapes du projet

### 1. **Importation des données**

L'ensemble de données Titanic a été téléchargé depuis Kaggle. Nous avons chargé les données dans un DataFrame pour commencer l'exploration et le nettoyage.

### 2. **Exploration des données**

Avant d'appliquer des techniques de machine learning, nous avons examiné chaque colonne de l'ensemble de données pour comprendre la nature des informations disponibles. Cette exploration nous a permis d'identifier les colonnes pertinentes pour la prédiction de la survie des passagers.

### 3. **Nettoyage des données**

Le nettoyage des données est une étape essentielle. Nous avons vérifié la qualité des données en traitant les valeurs manquantes et en éliminant les anomalies. Par exemple, les valeurs manquantes pour l'âge ont été traitées en remplissant les cases vides avec la médiane des âges.

### 4. **Gestion des valeurs aberrantes**

Certaines colonnes de l'ensemble de données contenaient des valeurs aberrantes qui pouvaient influencer négativement la performance du modèle. Nous avons identifié ces valeurs et les avons traitées de manière appropriée pour garantir la précision de nos prédictions.

### 5. **Visualisation des données**

Pour mieux comprendre les relations entre les différentes variables, nous avons utilisé des visualisations graphiques. Ces visualisations ont permis de mieux cerner les tendances et les patterns dans les données, en particulier pour la survie des passagers en fonction de certaines variables comme le sexe, l'âge et la classe.

### 6. **Ingénierie des fonctionnalités**

L'ingénierie des fonctionnalités est une étape importante pour améliorer la performance du modèle. Nous avons créé de nouvelles variables en extrayant des informations pertinentes à partir des colonnes existantes, comme la taille de la famille et le jour de la semaine d'embarquement. Ces nouvelles fonctionnalités ont été utilisées pour enrichir notre modèle.

### 7. **Mise à l'échelle des données**

Nous avons mis à l'échelle les données pour assurer que les différentes caractéristiques aient un impact similaire sur le modèle. Cette étape est cruciale pour éviter que certaines variables, telles que l'âge ou le tarif, ne dominent les autres.

### 8. **Séparation des données en ensembles d'entraînement et de test**

Pour évaluer la performance de notre modèle, nous avons séparé les données en deux ensembles : un pour l'entraînement et un pour le test. Cette division nous a permis d'évaluer le modèle sur des données qu'il n'a pas vues pendant l'entraînement.

### 9. **Application des modèles de machine learning**

Nous avons appliqué plusieurs algorithmes de machine learning à l'ensemble de données, en utilisant des techniques comme la sélection des caractéristiques pour améliorer les prédictions. Le modèle le plus performant dans ce projet était le Gradient Boosting Classifier, qui a montré les meilleurs résultats pour prédire la survie des passagers.

### 10. **Conclusion**

Ce projet a permis de construire un modèle efficace pour prédire la survie des passagers du Titanic. L'analyse des données, le nettoyage, et l'ingénierie des fonctionnalités ont été des étapes clés pour améliorer la performance du modèle.

---

## Comment exécuter le projet

1. Téléchargez le fichier du projet.
2. Remplacez l'URL par `CMT` dans le fichier.
3. Exécutez le fichier Jupyter Notebook pour suivre l'analyse étape par étape.
