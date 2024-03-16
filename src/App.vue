<template>
  <div class="container">
    <div class="welcome">
      <h1>Bienvenidos a mi Blogggg</h1>
      <img 
        src="https://i.pinimg.com/236x/b6/ef/77/b6ef77457af02e5a597703e4903a1dad.jpg"
        alt="Imagen descriptiva">
      <p class="">
        Esta es una super descripción genérica para el blog de como usar sass. Aquí podrás encontrar contenido sobre programación, tecnología, y mucho más.
      </p>
      <div class="social-media">
        <a 
          href="https://facebook.com"
          target="_blank">
          <img 
            src="https://i.pinimg.com/236x/56/30/d2/5630d2355f9da80b900fd4523389d169.jpg" 
            alt="Facebook">
        </a>
        <a 
          href="https://twitter.com"
          target="_blank">
          <img 
            src="https://i.pinimg.com/236x/07/df/57/07df57f369b03a4cc85a94bfb7002db9.jpg" 
            alt="Twitter">
        </a>
        <a 
          href="https://instagram.com"
          target="_blank">
          <img 
            src="https://i.pinimg.com/236x/73/ec/fe/73ecfe9b8b2801adf54eb66e58efc4dd.jpg"
            alt="Instagram">
        </a>
      </div>
    </div>
  </div>
</template>

<style>
.welcome {
  text-align: center;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 100vh;
}

.welcome img {
  margin-top: 20px;
  width: 150px;
  height: auto;
  border-radius: 10px;
}

.social-media {
  margin-top: 20px;
}

.social-media a {
  margin: 0 10px;
}

.social-media img {
  width: 40px;
  height: 40px;
  transition: transform 0.3s ease;
}

.social-media img:hover {
  transform: scale(1.1);
}
</style>
