Ce guide vous permet d’apprendre comment utiliser notre programme Deckard.

Assurez vous que vous avez une caméra et un microphone enregistrés par défaut sur votre ordinateur.

1-	Si vous avez déjà une base de données d’utilisateurs :

Si vous avez déjà une base de données d’utilisateurs que vous souhaitez fournir au programme, place vos images au forme .jpg ou .jpge dans un dossier Data dans la racine du programme.
Ensuite exécutez le programme : saving_face_encodings.py
Ce code enregistre juste les encodings des images fournis dans le dossier data dans un fichiers dataset_faces.dat, et ne les conserve en aucun cas.

2-	Si vous n’avez pas de base de données :

Exécutez directement le programme DECKARD.py

Vous pouvez aussi réaliser des tests sur notre programme. 

-	Pour cela, munissez-vous d’une base de données « train » pour entrainer le modèle, et une basse donnée « test » pour réaliser des tests sur la précision du programme.

-	Déposez les images « train » dans un dossier : bdd_train 

-	Déposez les images « test » dans un dossier : bdd_test

-	Exécutez ensuite le programme : test_facerecog.py

-	Vous aurez un résultat de la forme :  Accuracy = 99.75858369098712 %
