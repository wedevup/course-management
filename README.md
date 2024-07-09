# Desafio Back-end

Este projeto contém dois recursos essenciais para o funcionamento da aplicação, o recurso `cursos` e o recurso `alunos`.

Você deverá implementar funcionalidades a partir desses recursos.

# Informações importantes:

- O projeto está sobre o framework NestJS
- O banco de dados é SQLite
- Está sendo usado o ORM TypeORM para consultas/alterações no banco de dados
- A flag `synchronize` está ativa no TypeORM para que não seja necessária a criação de migrations

# Entre suas tarefas estão:

1. Adicionar a possibilidade de cadastro e alteração de preço de um curso;
2. Adicionar a possibilidade de expirar um curso, podendo estar expirado ou não;
3. Gerar um número de matrícula para os alunos cada vez que forem cadastrados;
4. Adicionar a possibilidade de cadastrar e descadastrar alunos à cursos;
5. Migrar a geração de de número de matrícula do aluno para cada um de seus cursos.

# Perguntas:

1. Esse sistema é muito simples e tem potenciais problemas de segurança, você consegue identificar um ou mais deles??
