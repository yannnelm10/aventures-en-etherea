<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aventures en Terre d’Éthéria</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <!-- Carte du jeu -->
        <div id="map">
            <h2>Carte de la Terre d’Éthéria</h2>
            <canvas id="gameCanvas" width="800" height="600"></canvas>
        </div>
        
        <!-- Zone d'informations -->
        <div id="stats">
            <h3>Personnage</h3>
            <p><strong>Nom :</strong> <span id="characterName">Aventurier</span></p>
            <p><strong>Santé :</strong> <span id="health">100</span></p>
            <p><strong>Magie :</strong> <span id="magic">50</span></p>
        </div>

        <!-- Zone d'inventaire -->
        <div id="inventory">
            <h3>Inventaire</h3>
            <ul id="items">
                <li>Potion de soin</li>
            </ul>
        </div>
    </div>

    <script src="game.js"></script>
</body>
</html>
