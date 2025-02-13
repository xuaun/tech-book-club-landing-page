# Frontend Mentor - Tech book club landing page solution

## Languages
This first section is in English. 

[Versão em português logo abaixo.](#portuguese)

## Context

This is a solution to the [Tech book club landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

> Your challenge is to build out this landing page and get it looking as close to the design as possible.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

#### Desktop

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Desktop Screenshot of live page" title="Desktop Screenshot of live page" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Tablet Screenshot of live page" title="Tablet Screenshot of live page" width="450px" />
</p>

#### Mobile

<p align="center">
  <img src="./src/design/mobile-screenshot.png" alt="Mobile Screenshot of live page" title="Mobile Screenshot of live page" width="300px" />
</p>

### Links

- Solution URL: [GitHub Repository](https://your-solution-url.com) and [my Frontend Mentor solution page](https://your-live-site-url.com)
- Live Site URL: [Live Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Query + clamp()

### What I learned

In this project I was able to use flexbox, grid, variable, and media query concepts in CSS, as well as using a ready-made Figma design to create this component. I also used `rem` for measurements, `clamp()` to help with responsiveness, and BEM methodology for naming classes.

```css
.info {
  display: grid;
  grid-template-areas:
    "pic-1 body-1"
    "body-2 pic-2";
  column-gap: 8rem;
  row-gap: 12rem;
  align-items: center;
  margin: 0rem clamp(1.6rem, -2.59rem + 11.174vw, 13.5rem);
}
```

## Author

- Website - [João Víctor de Araujo Lima's Portfolio](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)

____
<br>

# <p id="portuguese">Frontend Mentor - Solução do projeto de Landing page do clube do livro de tecnologia</p>

## Contexto

Esta é uma solução para o [desafio de landing page do clube do livro de tecnologia no Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

> Seu desafio é criar esta landing page e fazer com que ela tenha a aparência mais próxima possível do design.

## Lista de conteúdos

- [Visão Geral](#visão-geral)
  - [Desafio](#desafio)
  - [Prints](#prints)
  - [Links](#links-pt)
- [Meu processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

## Visão Geral

### Desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal dependendo do tamanho da tela do dispositivo
- Veja os estados de hover e focus para todos os elementos interativos na página

### Prints

#### Computador

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Print da tela no Desktop" title="Print da tela no Desktop" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Print da tela no Tablet" title="Print da tela no Tablet" width="450px" />
</p>

#### Celular

<p align="center">
  <img src="./src/design/mobile-screenshot.png" alt="Print da tela no Celular" title="Print da tela no Celular" width="300px" />
</p>

### <p id="links-pt">Links</p>

- Link da solução: [Repositório no GitHub](https://github.com/xuaun/fylo-data-storage-component) e a [página da minha solução no Frontend Mentor](https://your-live-site-url.com)
- Site com a solução: [Página do projeto no ar](https://your-live-site-url.com)

## Meu processo

### Tecnologias utilizadas

- HTML5
- CSS
- Flexbox
- CSS Grid
- Media Query + calmp()

### O que eu aprendi

Neste projeto eu pude utilizar conceitos de flexbox e grid, de variáveis e de media query no CSS, além de usar um design pronto do Figma para a elaboração deste componente. Eu também usei `rem` para medidas, `clamp()` para ajudar na responsividade e metodologia BEM para nomear classes.

```css
.info {
  display: grid;
  grid-template-areas:
    "pic-1 body-1"
    "body-2 pic-2";
  column-gap: 8rem;
  row-gap: 12rem;
  align-items: center;
  margin: 0rem clamp(1.6rem, -2.59rem + 11.174vw, 13.5rem);
}
```

## Autor

- Website - [Portfólio - João Víctor de Araujo Lima](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)

