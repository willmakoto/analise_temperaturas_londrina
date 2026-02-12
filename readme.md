# Análise da Variação da Temperatura Máxima em Londrina/PR (1961-2019)

Este projeto analisa a variação da temperatura máxima na cidade de Londrina/PR ao longo de 59 anos, evidenciando padrões sazonais e tendências de variação ao longo do período analisado. Para visualizar a evolução dos dados, foi desenvolvido um gráfico polar dinâmico, condensado em um GIF animado.

## 🔍 Objetivo do Projeto

Demonstrar um fluxo completo de análise de dados:

- Ingestão de dados brutos
- Limpeza e transformação
- Visualização personalizada com Matplotlib

## 🗂️ Estrutura do Projeto

- `dados/brutos`: dados originais sem tratamento
- `dados/processados`: dados tratados e agregados
- `notebooks`: etapas do pipeline de dados e análise
- `outputs`: visualizações finais

## 🐍 Tecnologias utilizadas:

- Python para análise e visualização dos dados
- Pandas e NumPy para manipulação dos dados
- Matplotlib para construção dos gráficos

## 🧠 Principais aprendizados e desafios:

- Coleta, limpeza e tratamento de dados climáticos
- Manipulação eficiente de DataFrames no Pandas
- Criação de visualizações personalizadas com Matplotlib
- Automação da geração de imagens para criar um GIF
- Análise de tendências de temperatura ao longo dos anos

## 🖼️ Resultado Final

As imagens geradas foram utilizadas para a criação de uma representação visual na forma de um GIF:

<p align="center">
  <img src="temperatura_novo.gif" width="60%">
</p>

Cada ponto representa a média mensal de temperatura máxima para um mês de um determinado ano. A animação permite observar padrões sazonais e variações ao longo das décadas.

## 🔄 Como reproduzir o projeto

### Requisitos

- Python 3.9 ou superior
- Git instalado

---

1. Clone o repositório:

```
git clone https://github.com/willmakoto/analise_temperaturas_londrina.git
cd analise_temperaturas_londrina

```
2. Crie um ambiente virtual:

```
python -m venv venv
```
Ative o ambiente virtual

3. Se estiver utilizando Windows:

```
venv\Scripts\activate
```
4. Se estiver utilizando Linux/Mac:

```
source venv/bin/activate
```

5. Instale as dependências:

```
pip install -r requirements.txt
```

6. Execute os notebooks:

```
jupyter notebook
```
Execute os notebooks na pasta `notebooks` na seguinte ordem:

1. 01_limpeza_transformacao_dados.ipynb

2. 02_aplica_dados_imprime_frames.ipynb


O GIF final pode ser gerado a partir das imagens em `outputs`.

---

A inspiração desse projeto veio a partir do trabalho de [Alvaro Franco Martins](https://www.linkedin.com/feed/update/urn:li:activity:7296902314588565504/)

Fonte dos dados: [DataClimaBR](https://ee-deborapdsouza.projects.earthengine.app/view/dataclimabr)