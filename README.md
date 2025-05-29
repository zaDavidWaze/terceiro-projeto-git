# **📘 Dicionário da EAP**

## **1. Levantamento de requisitos**

| Código | Pacote de Trabalho              | Descrição                                                                                                         | Recursos Necessários                       | Critérios de Aceitação                                                           | Responsável |
| ------ | ------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------ | -------------------------------------------------------------------------------- | ----------- |
| 1.1    | Entrevistas com usuários        | Realizar entrevistas com os usuários finais para entender suas necessidades e expectativas em relação ao sistema. | Sala de reunião, gravador de áudio         | Relatório com transcrição das entrevistas e análise das informações coletadas    |Monise|
| 1.2    | Análise de processos existentes | Estudar os processos atuais de gestão de cursinhos para identificar pontos de melhoria.                           | Acesso a documentos e processos existentes | Relatório de análise com identificação de ineficiências e sugestões de melhorias |Juliano|
| 1.3    | Definição de funcionalidades    | Determinar as funcionalidades essenciais do sistema com base nas entrevistas e análise de processos.              | Ferramentas de documentação                | Documento de especificação funcional aprovado pela equipe                        |Juliano|


## **2. Desenvolvimento do Sistema**

| Código | Pacote de Trabalho            | Descrição                                                                                                 | Recursos Necessários                                              | Critérios de Aceitação                                                  | Responsável |
| ------ | ----------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ----------------------------------------------------------------------- | ----------- |
| 2.1    | Arquitetura do sistema        | Definir a arquitetura técnica do sistema, incluindo escolha de tecnologias e estrutura de banco de dados. | Ferramentas de modelagem                                          | Documento de arquitetura aprovado pela equipe técnica                   |             |
| 2.2    | Desenvolvimento do backend    | Implementar a lógica de negócios e APIs do sistema utilizando PHP.                                        | Ambiente de desenvolvimento PHP, servidor local, editor de código | Código funcional com cobertura de testes unitários                      |Daniel|
| 2.3    | Desenvolvimento do frontend   | Criar a interface do usuário utilizando HTML e CSS, garantindo responsividade e usabilidade.              | Editor de código, navegador para testes, frameworks CSS           | Interface funcional validada por testes de usabilidade                  |Laura|
| 2.4    | Integração com banco de dados | Conectar o sistema ao banco de dados MySQL, implementando operações CRUD.                                 | Acesso ao banco de dados MySQL, ferramentas de gerenciamento      | Sistema integrado com banco de dados, realizando operações corretamente |Monise|


## **3. Testes e Validação**

| Código | Pacote de Trabalho    | Descrição                                                                                             | Recursos Necessários                             | Critérios de Aceitação                                                     | Responsável |
| ------ | --------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------ | -------------------------------------------------------------------------- | ----------- |
| 3.1    | Testes unitários      | Realizar testes individuais nas funções e métodos do sistema para garantir seu correto funcionamento. | Framework de testes, ambiente de desenvolvimento | Cobertura de testes mínima de 80%, sem falhas críticas                     |             |
| 3.2    | Testes de integração  | Verificar a interação entre os diferentes módulos do sistema, garantindo sua integração adequada.     | Ambiente de integração, ferramentas de testes    | Todos os módulos integrados funcionando conforme esperado                  |             |
| 3.3    | Testes de usabilidade | Avaliar a interface do usuário com usuários reais para identificar possíveis melhorias.               | Usuários para testes, ferramentas de feedback    | Relatório com feedback dos usuários e sugestões de melhorias implementadas |             |


## **4. Implantação e Treinamento**

| Código | Pacote de Trabalho                  | Descrição                                                                            | Recursos Necessários                                                  | Critérios de Aceitação                                         | Responsável |
| ------ | ----------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------- | -------------------------------------------------------------- | ----------- |
| 4.1    | Implantação em ambiente de produção | Disponibilizar o sistema para uso real, configurando servidores e realizando deploy. | Servidores de produção, ferramentas de deploy                         | Sistema funcionando corretamente em ambiente de produção       |             |
| 4.2    | Treinamento de usuários             | Capacitar os usuários finais para utilizar o sistema de forma eficiente.             | Material de treinamento, sala para sessões, equipamentos audiovisuais | Feedback positivo dos usuários sobre a eficácia do treinamento |             |


## **5. Encerramento do Projeto**

| Código | Pacote de Trabalho      | Descrição                                                                                          | Recursos Necessários                               | Critérios de Aceitação                             | Responsável |
| ------ | ----------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------- | -------------------------------------------------- | ----------- |
| 5.1    | Documentação final      | Elaborar documentação técnica e de usuário do sistema.                                             | Ferramentas de documentação                        | Documentação completa e aprovada pela equipe       |             |
| 5.2    | Reunião de encerramento | Realizar reunião final com a equipe e stakeholders para apresentar resultados e lições aprendidas. | Sala de reunião, apresentações, materiais de apoio | Registro da reunião com feedback dos participantes |             |










.
.
.
.
.
.
.
.
.
.
.
.

.

.
.
.
.

.

.

.



.

..

.
.

.

.
# Backlog Terceiro Semestre

| ID  | Item                     | História de Usuário                                                                                                                                         | Tarefas Técnicas                                                                                                                                                       | Prioridade | Complexidade | Nível |
|------|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------------|-------|
| 1.1  | Cadastro de Alunos     | COMO administrador do sistema, QUERO cadastrar novos alunos com dados essenciais, PARA iniciar o registro acadêmico                                        | Banco de Dados: Modelar tabela alunos com campos obrigatórios e CPF único                                                                                            |            |              |       |
| 1.2  |                        |                                                                                                                                                             | Backend: CRUD e conexão com o banco de dados                                                                                                                         |            |              |       |
| 1.3  |                        |                                                                                                                                                             | Frontend: Criar formulário responsivo com máscaras (CPF/telefone)                                                                                                     |            |              |       |
| 1.4  |                        |                                                                                                                                                             | Prototipagem: Protótipo de tela com validações visuais                                                                                                               |            |              |       |
| 2.1  | Cadastro Básico de Turmas | COMO administrador do sistema, QUERO registrar novas turmas com informações básicas, PARA organizar as turmas                                               | Banco de Dados: Modelar tabela turmas relacionadas                                                                                                                    |            |              |       |
| 2.2  |                        |                                                                                                                                                             | Backend: CRUD e conexão com o banco de dados                                                                                                                         |            |              |       |
| 2.3  |                        |                                                                                                                                                             | Frontend: Componente de seleção de cursos (dropdown)                                                                                                                 |            |              |       |
| 2.4  |                        |                                                                                                                                                             | Prototipagem: Protótipo de tela com validações visuais                                                                                                               |            |              |       |
| 3.1  | Dashboard Parcial      | COMO administrador do sistema, QUERO uma tela inicial simplificada, PARA acessar rapidamente as funções principais disponíveis nessa versão                 | Prototipagem: Protótipo de tela inicial                                                                                                                               |            |              |       |
| 3.2  |                        |                                                                                                                                                             | Frontend: Menu de navegação principal                                                                                                                                 |            |              |       |
| 4.1  | Consulta de Alunos     | COMO administrador do sistema, QUERO buscar e visualizar alunos cadastrados, PARA verificar informações                                                      | Backend: Pesquisa de informações no banco de dados                                                                                                                   |            |              |       |
| 5.1  | Edição de Alunos       | COMO administrador do sistema, QUERO editar informações dos alunos existentes, PARA manter dados atualizados                                                 | Backend: Reescrever dados dos alunos no banco de dados                                                                                                               |            |              |       |
| 6.1  | Consulta de Turmas     | COMO administrador do sistema, QUERO visualizar turmas cadastradas, PARA gerenciar a alocação de alunos                                                      | Backend: Pesquisa de informações no banco de dados                                                                                                                   |            |              |       |
| 7.1  | Edição de Turmas       | COMO administrador do sistema, QUERO modificar dados de turmas existentes, PARA ajustar informações                                                          | Backend: Reescrever dados das turmas no banco de dados                                                                                                               |            |              |       |
| 8.1  | Gerenciamento de Turmas | COMO administrador do sistema, QUERO ativar/inativar turmas, PARA adaptar à demanda acadêmica                                                                | Frontend: Criar Formulário responsivo                                                                                                                                 |            |              |       |
| 8.2  |                        |                                                                                                                                                             | Backend: CRUD e conexão com o banco de dados                                                                                                                         |            |              |       |
| 8.3  |                        |                                                                                                                                                             | Banco de Dados: Modelar tabela de gerenciamento de turmas                                                                                                            |            |              |       |
