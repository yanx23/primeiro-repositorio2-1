/* Reset básico e estilos do corpo */
body {
    font-family: sans-serif;
    margin: 0;
    background-color: #f4f4f4;
  display: flex;
  flex-direction:column;
}

/* Estilizando o contêiner da navbar */
.navbar-container {
    background-color: #333;
    padding: 15px;
    color: white;
}

/* Estilizando os links dentro da navbar para melhor visualização */
.navbar-container a {
    color: white;
    text-decoration: none;
    margin: 0 10px; /* Adiciona um espaço entre os links */
    font-size: 18px;
}

.logo a {
    font-weight: bold;
    font-size: 24px;
}
   
/* Aqui começa o flexbox */
.navbar-container{
  display: flex;
  justify-content: space-between;
  align-intems;center;
}
