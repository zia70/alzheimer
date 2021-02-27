# alzheimer_classification_STADES


Le diagnostic de la maladie d’Alzheimer repose sur un bilan complet des capacités cognitives de la personne (IRM, questionnaires…). Il est généralement effectué dans le cadre d’une consultation mémoire. Toutefois, il n’existe pas de test Alzheimer spécifique et il est impossible de dépister la maladie à un stade précoce. En effet, l’analyse anatomique du cerveau par IRM (imagerie par résonance magnétique) consiste habituellement à mesurer l’épaisseur du cortex cérébral ou le volume de plusieurs régions du cerveau comme l’hippocampe, dont l’atrophie est un des premiers signes de la maladie d’Alzheimer. Cette méthode permet de détecter la maladie correctement dans environ 80% des cas.. Dans ce projet, nous avons utilisé les données publiques d'IRM cérébrale issues de l'étude de la maladie d'Alzheimer (Le test contient 1279 images et le training contient 5121 images) afin de tester quelques modèles très précis pour classifier le stade de la maladie d'Alzheimer.nous avons testé différents modèles de classification à savoir : vgg19, vgg16, DenseNet121, MobileNet, DenseNet169.  Pour évaluer la performance des modèles utilisés, nous avons dû créer des représentations graphiques en concentrant notre attention sur la précision « Accuracy » et la perte « Loss ». 
The dataset used can be found here. https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images
