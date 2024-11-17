
<head>
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>🎉 ¡Feliz Cumpleaños! 🎉</title>
        <style>
            body {
                margin: 0;
                padding: 0;
                font-family: 'Arial', sans-serif;
                background: linear-gradient(135deg, #ff9a9e, #fad0c4);
                text-align: center;
                color: #333;
            }
    
            .container {
                max-width: 800px;
                margin: auto;
                padding: 20px;
            }
    
            h1 {
                font-size: 3rem;
                color: #ff69b4;
                text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            }
    
            p {
                font-size: 1.5rem;
                margin: 20px 0;
                color: #555;
            }
    
            .btn {
                display: inline-block;
                padding: 15px 30px;
                font-size: 1.2rem;
                font-weight: bold;
                color: white;
                background: #ff69b4;
                border: none;
                border-radius: 50px;
                cursor: pointer;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
                transition: all 0.3s ease;
                text-transform: uppercase;
            }
    
            .btn:hover {
                background: #ff1493;
                transform: scale(1.1);
            }
    
            #galeria {
                display: none; /* Ocultado por defecto */
                margin-top: 20px;
            }
    
            .galeria {
                display: flex;
                flex-wrap: wrap;
                gap: 10px;
                justify-content: center;
            }
    
            .galeria img {
                width: 150px;
                height: 150px;
                object-fit: cover;
                border-radius: 10px;
                box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
                transition: transform 0.3s ease, box-shadow 0.3s ease;
            }
    
            .galeria img:hover {
                transform: scale(1.1);
                box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            }
    
            footer {
                margin-top: 40px;
                font-size: 1rem;
                color: #666;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <h1>🎉 ¡Feliz Cumpleaños, Amor! 🎉</h1>
            <p>
                Hoy celebramos a la persona más especial en mi vida. Cada momento contigo es mágico. <br> 
                ¡Te amo con todo mi corazón! 💖
            </p>
    
            <!-- Botón para mostrar la galería -->
            <button class="btn" onclick="mostrarGaleria()">Ver momentos especiales 📸</button>
            
            <!-- Contenedor de la galería -->
            <div id="galeria">
                <div class="galeria">
                    <img src="ALIII.jpeg." alt="Momento Especial 1">
                    <img src="LISITA.jpeg" alt="Momento Especial 2">
                    <img src="ALIIIIIIII.jpeg" alt="Momento Especial 3">
                    <img src="GATITOO.jpeg" alt="Momento Especial 4">
                    <img src="ALII.jpeg" alt="Momento Especial 5">
                    <img src="ALLALA.jpeg" alt="Momento Especial 6">
                </div>
            </div>
    
            <!-- Botón para ir al video -->
            <button class="btn" style="margin-top: 30px;" onclick="irAVideo()">Ir a mi regalo especial 🎥</button>
        </div>
    
        <footer>
            💖 Con todo mi amor, siempre a tu lado. 💖
        </footer>
    
        <script>
            function mostrarGaleria() {
                const galeria = document.getElementById('galeria');
                if (galeria.style.display === 'none' || galeria.style.display === '') {
                    galeria.style.display = 'block';
                } else {
                    galeria.style.display = 'none';
                }
            }
    
            function irAVideo() {
                window.open('https://youtu.be/CkXjzqUpjyg?si=_iZ1zcDhvpC_wSto', '_blank');
            }
        </script>
    </body>
    </html>
    