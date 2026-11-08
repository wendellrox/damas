# ♟️ Jogo de Damas Clássicas (Player vs CPU)

Um jogo de damas completo, responsivo e interativo feito em HTML5, CSS3 e JavaScript puro, projetado com foco em telas touch de dispositivos móveis e navegadores web.

---

## 📸 Recursos e Destaques

- **Regras Oficiais Brasileiras (Padrão):**
  - **Dama Voadora:** Movimenta-se e captura em longas diagonais a qualquer distância.
  - **Captura para trás:** Peças comuns podem capturar para frente e para trás.
  - **Lei da Maioria:** Obrigatoriedade de realizar a tomada com o maior número de peças.
  - **Captura Obrigatória:** Sem sopros; lances com captura são obrigatórios e sinalizados na interface.
- **Modo Regras Internacionais:** Alternância rápida entre regra brasileira e padrão internacional.
- **Inteligência Artificial (CPU):**
  - 3 níveis de dificuldade: **Iniciante**, **Médio** e **Mestre**.
  - Algoritmo **Minimax com Poda Alpha-Beta** e avaliação posicional (controle de centro, avanço e proteção da última linha).
- **Assistente de Partida:**
  - Botão **Dica (💡)** com cálculo do melhor lance.
  - Botão **Desfazer (↩️)** para corrigir jogadas.
- **Experiência Sensorial:**
  - Sintetizador de áudio via **Web Audio API** (sem arquivos de áudio externos, 100% offline).
  - **Feedback Háptico (Vibração)** no toque ao mover ou capturar peças no celular.
- **Customização:**
  - 3 temas visuais: *Clássico Madeira*, *Escuro Moderno* e *Esmeralda Luxo*.

---

## 🚀 Como Executar

Por ser uma aplicação web estática autossuficiente (sem dependências externas), basta abrir o arquivo `index.html` em qualquer navegador:

```bash
# Executando localmente via Python:
python3 -m http.server 8080
```

Acesse: `http://localhost:8080`

---

## 📄 Licença

Distribuído sob a licença MIT. Sinta-se livre para usar, estudar e modificar.
