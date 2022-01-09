<template>
  <div class="container">
    <h1>Werken Wout!</h1>
  </div>
  <img alt="Tech Express logo" class="logo" src="./assets/logo.svg" />
</template>

<style>
:root {
  height: 100%;
}

body {
  background-color: #111827;
  height: 100%;
  margin: 0;
}

.container {
  display: flex;
  flex-grow: 1;
  align-items: center;
}

h1 {
  font-size: 12vw;
}

#app {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
  font-family: "Staatliches", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}

.logo {
  width: 80px;
  margin-bottom: 24px;
}
</style>
