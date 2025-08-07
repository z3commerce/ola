<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Te amo, Tainara ❤️</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffe6f0, #ffccda);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Arial', sans-serif;
    }

    .coracao {
      font-size: 5rem;
      color: #ff0055;
      animation: pulsar 1s infinite;
    }

    .mensagem {
      font-size: 2.5rem;
      color: #d10068;
      text-align: center;
      margin-top: 20px;
      font-weight: bold;
    }

    .link {
      display: inline-block;
      margin-top: 40px;
      font-size: 1.5rem;
      color: #ffffff;
      background-color: #d10068;
      padding: 12px 24px;
      border-radius: 10px;
      text-decoration: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: 0.3s;
    }

    .link:hover {
      background-color: #a00050;
      transform: scale(1.05);
    }

    @keyframes pulsar {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="coracao">❤️</div>
  <div class="mensagem">Te amo, Tainara</div>
  <a class="link" href="https://www.youtube.com/watch?v=450p7goxZqg" target="_blank">Ouça essa música 💖</a>

  <audio autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    Seu navegador não suporta áudio.
  </audio>
</body>
</html>
