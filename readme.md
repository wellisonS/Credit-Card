# Previsão de Churn de Clientes Bancários

## Visão Geral
Este projeto foca na previsão de churn (evasão) de clientes no setor bancário. O churn de clientes, que se refere à perda de clientes, é um problema crítico para os bancos, pois a retenção de clientes é essencial para garantir lucratividade e crescimento. O objetivo deste projeto é analisar os dados dos clientes, realizar o pré-processamento dos dados e construir modelos de aprendizado de máquina para prever quais clientes têm maior probabilidade de sair.

## Definição do Problema
No setor bancário, a retenção de clientes é fundamental para manter a lucratividade. Compreender os fatores que levam os clientes a deixar o banco pode ajudar a tomar medidas preventivas. Neste projeto, o objetivo é analisar um conjunto de dados de clientes bancários, explorar os dados e criar modelos para prever o churn de clientes.

## Conjunto de Dados
O conjunto de dados utilizado nesta análise está relacionado ao churn de clientes bancários e contém várias características, incluindo:
- Informações demográficas
- Atributos relacionados à conta bancária
- Uso do cartão de crédito
- Histórico de transações e saldo

## Principais Etapas do Projeto
### 1. Processamento de Dados
- **Importação dos Dados**: Importação do conjunto de dados e das bibliotecas necessárias, como `pandas`, `numpy` e `seaborn`.
- **Limpeza dos Dados**: Remoção de colunas irrelevantes, tratamento de valores ausentes e codificação de dados categóricos.
- **Exploração dos Dados**: Realização de análise exploratória dos dados (EDA) para entender as relações entre as variáveis independentes e o churn (variável alvo).

### 2. Análise Exploratória de Dados (EDA)
- **Visualização**: Utilização das bibliotecas `seaborn` e `matplotlib` para criar gráficos de distribuição e correlações.
- **Insights**: Obtenção de insights a partir do conjunto de dados, visualizando variáveis-chave que podem influenciar o churn de clientes.

### 3. Engenharia de Atributos
- Criação de novas variáveis com base nos dados existentes para melhorar o desempenho dos modelos.
- Normalização de variáveis numéricas.
- Codificação de variáveis categóricas para os modelos de aprendizado de máquina.

### 4. Construção de Modelos
- **Seleção de Modelos**: Vários modelos foram avaliados, incluindo Regressão Logística, Árvore de Decisão e Random Forest.
- **Treinamento e Teste**: O conjunto de dados foi dividido em conjunto de treinamento e teste para avaliar a acurácia e o desempenho dos modelos.
- **Avaliação de Modelos**: Os modelos foram avaliados usando métricas como acurácia, precisão, recall e F1-score para identificar o modelo mais eficaz.

### 5. Resultados
A análise revelou insights importantes sobre os fatores que contribuem para o churn de clientes, como a atividade da conta e o tempo de relacionamento com o banco. O modelo com melhor desempenho forneceu um equilíbrio entre precisão e recall, permitindo previsões eficazes de churn.

## Conclusão
Este projeto demonstra a importância de compreender o comportamento dos clientes e aplicar modelos preditivos para antecipar o churn. Os insights gerados a partir dessa análise podem ajudar os bancos a desenvolver estratégias para reter clientes valiosos.



## Informações de Contato
- **LinkedIn**: [https://www.linkedin.com/in/wellison-silva/]

