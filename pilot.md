# Criando sua Primeira Aplicação com Vite e React

> by Xaianax 


Este tutorial vai te guiar pela criação de uma aplicação React usando o Vite, uma ferramenta moderna e ultrarrápida para construção de front-ends. Ideal para quem quer aprender na prática, com passos simples e diretos.

---

## Pré-requisitos

Antes de começar, certifique-se de que você tem instalado:

- [Node.js](https://nodejs.org/) (v18 ou superior)
- [Git](https://git-scm.com/)
- [Visual Studio Code (VS Code)](https://code.visualstudio.com/)

---

## Passo 1 – Criar o Projeto com Vite

Abra o terminal do VS Code com `Ctrl + '` (aspas simples). Em seguida, execute o comando abaixo para criar seu projeto:

```bash
npm create vite@latest
```

Quando solicitado:

- **Nome do projeto:** `tutorial-vite`
- **Framework:** `React`
- **Variante:** `JavaScript`

---

## Passo 2 – Acessar o Projeto

Após a criação do projeto, acesse a pasta:

```bash
cd tutorial-vite
```

E instale as dependências:

```bash
npm install
```

---

## Passo 3 – Executar a Aplicação

Para ver o projeto funcionando no navegador:

```bash
npm run dev
```

O terminal exibirá um endereço como `http://localhost:5173/`. Copie e cole no navegador.

---

## Passo 4 – Estrutura Inicial do Projeto

Seu projeto terá uma estrutura como:

```
tutorial-vite/
├─ public/
├─ src/
│  ├─ App.jsx
│  ├─ main.jsx
├─ index.html
├─ package.json
```

Você pode começar a editar o arquivo `App.jsx` para ver as mudanças em tempo real.

---

## Passo 5 – Personalize!

Abra `src/App.jsx` e edite o conteúdo para:

```jsx
function App() {
  return (
    <div>
      <h1>Olá, Liferay!</h1>
      <p>Essa é uma aplicação React criada com Vite.</p>
    </div>
  );
}

export default App;
```

---

## Passo 6 – Subir no GitHub (opcional)

1. Crie um repositório no GitHub.
2. No terminal, dentro da pasta do projeto, execute:

```bash
git init
git add .
git commit -m "primeiro commit"
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git push -u origin main
```

---

## Conclusão

Parabéns! 🎉  
Você acabou de criar e rodar sua primeira aplicação React com Vite. Isso mostra sua familiaridade com ferramentas modernas de desenvolvimento front-end — uma habilidade valiosa para posições como Technical Writer na Liferay.

---

**Happy coding! 🚀**