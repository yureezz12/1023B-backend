Documentação do Projeto
1. README (Arquivo principal do repositório)
Nome do Projeto:
Sistema de Cadastro e Listagem de Usuários e Produtos
Tema Escolhido:
Cadastro de Usuários e Produtos para uma loja ou sistema de gestão simples.
Descrição do Tema:
O sistema foi desenvolvido para realizar o cadastro e listagem de usuários e produtos. Ele é
útil para empresas que precisam de um controle básico de dados, com a possibilidade de
registrar informações em um banco de dados e consultar essas informações de forma
rápida e amigável.
Funcionalidades Implementadas:
● Cadastro de usuários (com id, nome e email)
● Listagem de usuários
● Cadastro de produtos (com id, nome e preço)
● Listagem de produtos
● Validação de dados
● Tratamento de erros do MySQL
● Interface responsiva com Bootstrap
Tecnologias Utilizadas:
● Back-end: Node.js + MySQL
● Front-end: HTML + CSS + JavaScript
Instruções para Rodar o Projeto Localmente:
Requisitos:
● Node.js instalado
● MySQL instalado e rodando
Banco de Dados:
1. Criar banco de dados:
CREATE DATABASE banco1023a;
2. Criar tabelas:
CREATE TABLE usuarios (
id INT PRIMARY KEY,
nome VARCHAR(100),
email VARCHAR(100)
);
CREATE TABLE produtos (
id INT PRIMARY KEY,
nome VARCHAR(100),
preco DECIMAL(10,2)
);
Rodando o projeto:
1. Clonar o repositório:
2. Instalar dependências:
npm install
3. Rodar o servidor:
