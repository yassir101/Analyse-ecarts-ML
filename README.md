# Détection de fraudes bancaires ML

Objectif : détecter des transactions frauduleuses à partir d’un jeu de données réel issu de Kaggle.

## Démarche

1. **Prétraitement** : normalisation des données.
2. **Visualisation** : analyse des corrélations, ACP pour réduction de dimension.
3. **Modèles testés** :
   - Régression logistique
   - Forêt aléatoire
   - SVM (avec ACP)
   - XGBoost
4. **Évaluation** : matrice de confusion, rapport de classification, AUC ROC.
5. 
## Résultats

- **Random Forest** et **XGBoost** offrent les meilleures performances.
- Tous les modèles ont été testés en prenant en compte le déséquilibre des classes.

## Remarques

Le projet réalisé sous Jupyter Notebook.  
Dataset: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud)

