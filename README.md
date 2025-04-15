## Sudoku 

![image](https://github.com/user-attachments/assets/e34f39ca-9804-4fff-90e2-212f6babc40f)
# Sudoku em Java

Este projeto é um jogo de Sudoku implementado em Java usando Swing para a interface gráfica. Ele apresenta um tabuleiro interativo 9x9 com validação de jogadas e contagem de erros.

## Funcionalidades

- Interface gráfica amigável
- Validação de números conforme solução correta
- Contador de erros exibido no topo
- Números selecionáveis para preenchimento das células vazias

## Como executar

1. Certifique-se de ter o Java instalado.
2. Compile o arquivo:
   ```bash
   javac Sudoku.java
## Estrutura
- Tile: Classe interna que representa uma célula do tabuleiro

- puzzle: Sudoku inicial com células preenchidas e vazias (-)

- solution: Gabarito usado para validação

- setupTiles(): Monta o tabuleiro

- setupButtons(): Cria botões de números (1-9) para seleção
