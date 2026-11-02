# PDE-Diary

## Semana 9 nov - 13 nov

## Semana 2 nov - 6 nov
- ...
- Elaboração do sprint 2 (slides e apresentação) para a cadeira de PDE.


## Semana 26 out - 30 out

- Continuação da leitura de artigos sobre Federated Learning descentralizado, com foco nos mecanismos de comunicação e agregação entre nós.
- Início da elaboração do estado da arte, sistematizando as abordagens estudadas e a sua relação com os objetivos da tese.
- Desenvolvimento do projeto complementar HVAA:
  - Implementação de um sistema de votação por consenso e de uma fase de revisão final das imagens.
  - Melhoria da interface de validação, incluindo a navegação nas imagens e a possibilidade de desfazer votos e correções recentes.
  - Evolução do site de avaliação das câmaras para recolher propostas de manutenção e de ajuste dos limiares de confiança.
  - Medição e otimização dos tempos de resposta, organização do código num repositório Git e documentação da arquitetura e do fluxo de validação.

## Semana 19 out - 23 out

- Leitura e síntese de artigos sobre Federated Learning centralizado e descentralizado, identificando diferenças nas arquiteturas e nas estratégias de coordenação.
- Definição da estrutura preliminar do estado da arte e organização das referências bibliográficas por tema.
- Desenvolvimento do projeto complementar HVAA:
  - Análise das limitações do primeiro MVP e implementação de um fluxo por fases para validar e corrigir deteções e anotar objetos em falta.
  - Preparação de conjuntos de imagens de diferentes câmaras e de um projeto separado no CVAT para avaliar a qualidade das deteções e os respetivos limiares de confiança.
  - Desenvolvimento inicial de um site de avaliação das câmaras e implementação de sessões de revisão e de um sistema de pontuação e classificação dos utilizadores.
  - Realização de testes de importação e validação com imagens captadas pelas câmaras reais.

## Semana 12 out - 16 out

- Preparação do ambiente de escrita da tese, incluindo a configuração do template, da estrutura inicial do documento e da bibliografia.
- Continuação da pesquisa bibliográfica sobre Federated Learning descentralizado e seleção de artigos para integrar no estado da arte.
- Desenvolvimento do projeto complementar HVAA:
  - Seleção de câmaras, organização das imagens e definição da estrutura de importação no CVAT, com um projeto por câmara e tarefas por lotes de imagens.
  - Análise das deteções automáticas e ajuste do limiar mínimo de confiança.
  - Evolução da interface para orientar a validação por classes e simplificar as escolhas do utilizador.
- Elaboração do sprint 1 (slides e apresentação) para a cadeira de PDE.

## Semana 5 out - 9 out

- Recolha de artigos que explorem Federated Learning descentralizado ou comparem FL centralizado e descentralizado.
- Investigação sobre FL síncrono e assíncrono (fora do âmbito do trabalho).
- Integração das câmaras no HVAA.
- Desenvolvimento da interface relativa ao projeto HVAA.
- Finalização do primeiro MVP da framework para realizar a validação humana das imagens anotadas automaticamente.
- Redefinição do fluxo de validação humana, com o objetivo de reduzir ao máximo os detalhes técnicos apresentados ao utilizador final, bem como o número de escolhas que este tem de fazer.

## Semana 28 set - 2 out

- Desenvolvimento de scripts para a ingestão automática de imagens no CVAT.
- Desenvolvimento de scripts para efetuar a anotação automática e interagir com a framework, permitindo comunicar os resultados da validação humana.
- Desenvolvimento de scripts que acedem aos servidores RTSP das câmaras e capturam imagens para utilização posterior no HVAA.

## Semana 21 set - 25 set

- Formalização de um projeto complementar, Human Validated Automatic Annotations (HVAA), que visa a criação de um dataset extenso e completo através de anotações automáticas posteriormente validadas por humanos.
- Definição dos objetivos do projeto complementar HVAA.
- Definição do fluxo de validação humana.
- Estudo do trabalho anterior relativo a este projeto.
- Estudo da framework proposta para este projeto (CVAT).
- Recolha e leitura de alguns artigos sobre Federated Learning, nomeadamente os citados na tese de mestrado de Bernardo Barreto.


## Semana 14 set - 18 set

- Formalização dos objetivos da tese.
- Distinção entre a tese e os trabalhos já realizados na mesma área, nomeadamente a tese de mestrado de Bernardo Barreto.
- Pesquisa sobre ferramentas de Federated Learning (Flower, NVIDIA FLare, TensorFlow Federated, PySyft e OpenFL): funcionamento, vantagens e desvantagens, principais casos de uso, funcionalidades específicas e suporte para utilização centralizada, descentralizada ou ambas.

## Anteriores

- Estudo da framework de Federated Learning disponível no IT (MobFedLS, desenvolvida por Bernardo Barreto).
- Contribuições para esta framework, nomeadamente suporte para múltiplas aplicações, robustez, testes automatizados e observabilidade.

## Alguns Acrónimos importantes

- **FL — Federated Learning (Aprendizagem Federada):** abordagem em que vários nós treinam um modelo com dados locais e partilham atualizações do modelo, sem centralizar os dados de treino.
- **ML — Machine Learning (Aprendizagem Automática):** área que desenvolve modelos capazes de aprender padrões a partir de dados.
- **HVAA — Human Validated Automatic Annotations:** projeto complementar para a criação de datasets através de anotações automáticas posteriormente validadas por humanos.
- **CVAT — Computer Vision Annotation Tool:** ferramenta de anotação de imagens e vídeos utilizada como base para o fluxo de anotação e validação do HVAA.
- **MVP — Minimum Viable Product (Produto Mínimo Viável):** primeira versão funcional com as funcionalidades essenciais para validar a solução.
- **IT — Instituto de Telecomunicações:** instituição onde está disponível a infraestrutura utilizada no trabalho.
- **RTSP — Real-Time Streaming Protocol:** protocolo utilizado para aceder às transmissões de vídeo das câmaras.
