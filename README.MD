# Sistema Web com Flask

Bem-vindo ao projeto de Sistema Web utilizando Flask! Este repositório contém o código-fonte de um sistema web construído com Flask, Python, HTML, CSS, JavaScript e SQL. Este projeto serve como um exemplo completo de uma aplicação web moderna.

## Índice

- [Introdução](#introdução)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#instalação)
- [Como Usar](#como-usar)

## Introdução

Este projeto é uma aplicação web construída com Flask, um microframework para Python. Ele inclui funcionalidades básicas de um sistema web, como autenticação de usuário, manipulação de dados com SQL, e uma interface de usuário dinâmica com HTML, CSS e JavaScript.

## Tecnologias Utilizadas

- **Flask**: Framework web para Python.
- **Python**: Linguagem de programação.
- **HTML**: Linguagem de marcação para criar a estrutura das páginas web.
- **CSS**: Linguagem de estilo para a apresentação das páginas web.
- **JavaScript**: Linguagem de programação para adicionar interatividade às páginas web.
- **SQL**: Linguagem de consulta para bancos de dados relacionais.

## Instalação

### Pré-requisitos

- Python 3.x
- pip (gerenciador de pacotes do Python)
- Banco de dados SQL (ex: SQLite, MySQL, PostgreSQL)

### Passos para Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Crie um ambiente virtual:
    ```bash
    python3 -m venv venv
    source .venv/bin/activate  # No Windows, use `.venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure o banco de dados:
    - Crie o banco de dados e as tabelas necessárias:
        ```bash
        flask db init
        flask db migrate -m "Initial migration."
        flask db upgrade
        ```

5. Execute a aplicação:
    ```bash
    flask run
    ```

## Como Usar

1. Acesse o sistema web em seu navegador através do endereço:
    ```
    http://127.0.0.1:5000/
    ```

2. Registre-se ou faça login para acessar as funcionalidades do sistema.

3. Navegue pelas diferentes páginas e utilize as funcionalidades disponíveis.

Agradeço por sua visita!
