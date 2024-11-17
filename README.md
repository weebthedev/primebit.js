# primebit.js

![npm version](https://img.shields.io/npm/v/primebit.js)
![license](https://img.shields.io/npm/l/primebit.js)

A clean and simple logging utility for Node.js applications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction

What is primebit? **primebit.js** is an npm package that gives users the ability to log things in a clean way! It provides developers with an efficient way to log messages in their Node.js applications, offering multiple log types and customization options to enhance your logging experience.

## Features

- **✨ Types**: Supports four different log types:
  
  - `log` (default)
  -  `error`
  -  `warning`
  -  `success`

## Miscellaneous

- **⚙️ Options**: different options to customize your logs:
  
   - `filled` - adds a filled color for the log.
     
> [!NOTE]  
> More options wil be added soon.


## Installation

To install primebit.js, you can do the following:

```bash
npm install primebit.js
```


## Example

```js
const p = require("primebit.js")

p.log("Hello World!", {
  options: {
    filled: true
  }
});
```


