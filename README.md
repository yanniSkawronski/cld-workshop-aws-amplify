# Workshop Cloud Computing : AWS Amplify

## Structure présentation

1. Introduction à AWS Amplify
2. Analyse des coûts
3. Risques de Vendor Lock-in
4. Présentation d'un Proof-of-concept
5. Recommandations d'utilisation, quand est-ce que l'outil est adapté et quand est-ce qu'il ne l'est pas


## Présentation d'AWS Amplify

### Présentation générale

Plateforme de développement permettant d'accélerer la création et la mise à disposition d'une application Web ou mobile, sans avoir à se préoccuper de la gestion de l'infrastructure serveur, et qui peut facilement être mis à l'échelle.

Flux de travail se base sur Git, outil largement utilisé dans le monde du développement, et configuration du backend dans le format "Infrastructure as Code", facilitant le suivi de l'infrastructure et sa réplication.

### Overview des outils

- Outil de CI/CD pour applications frontend
- Outil de gestion des services AWS dits "Backend"
- Librairies permettant d'intégrer les services backend dans l'application
- Une interface en ligne de commandes pour chapeauter le tout

Flux de travail basés sur Git. Supporte de nombreux frameworks frontend.

Permet un développement rapide et facilement scalable. On perd cependant en flexibilité, et tout fonctionne uniquement avec des outils de chez AWS. Cela peut cependant être une force si l'équipe travaille déjà avec AWS.


### Calcul des coûts

[Lien des différents coûts pour Amplify](https://aws.amazon.com/amplify/pricing/)

**Attention** : L'instance dont il est sujet ici est utilisée uniquement pour le build de l'application.

### Risque de vendor lock-in

Entièrement dans l'écosystème AWS. Interface propriétaire.
