# Dice Duel 🎲

“Refresh the page, roll the dice, and let fate decide the winner!”

Dice Duel is a simple two‑player dice challenge built with vanilla HTML, CSS, and JavaScript. Each time you reload the page, both players “roll” a die and the higher roll wins (or it’s a draw if both rolls are equal). It’s a small but fun project to practice DOM manipulation, randomness, and simple UI logic.

Live demo: https://yousefahmeddk.github.io/dice-duel/  
Repo: https://github.com/yousefahmeddk/dice-duel ([github.com](https://github.com/yousefahmeddk/dice-duel))

---

## Table of Contents

1. [Features](#features)  
2. [How It Works](#how-it-works)  
3. [Tech Stack](#tech-stack)  
4. [Getting Started / Setup](#getting-started)  
5. [Project Structure](#project-structure)  
6. [Usage](#usage)  
7. [Customization](#customization)  
8. [Contributing](#contributing)  
9. [License & Credits](#license-credits)  

---

## Features

- 🎲 Automatic dice roll on page load / refresh  
- 🔄 Random results every time  
- 🏆 Dynamic display of winner (Player 1, Player 2, or Draw)  
- Responsive, minimal UI  
- 100% vanilla JavaScript — no frameworks or external libraries used  
- Clean, lightweight code ideal for learning & small deployments  

---

## How It Works

1. When the page loads (or is refreshed), the JavaScript code triggers two random values (1 through 6) — one for each player.  
2. It updates the dice images (or text) in the DOM to reflect each player's roll.  
3. It compares the two values:
   - If Player 1’s value > Player 2’s value → display “Player 1 Wins”  
   - If Player 2’s value > Player 1’s value → display “Player 2 Wins”  
   - If they are equal → display “Draw”  
4. The user sees the result immediately without needing to click anything.

This logic is entirely contained in **index.js**.  

---

## Tech Stack

- HTML5 — basic page structure  
- CSS3 — styles, layout, responsive behavior  
- JavaScript (ES6) — core logic and DOM updates  
- No frameworks or external dependencies  

---

## Getting Started / Setup

You don’t need anything special — no build tools, no dependencies. Just clone and open.

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.)  
- (Optional) A local HTTP server (for better behavior in some browsers)  

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/yousefahmeddk/dice-duel.git
   ```

2. Navigate to the project folder:

   ```bash
   cd dice-duel
   ```

3. Open **index.html** in your browser (double‑click or via your server).

If you'd rather, you can serve it via a simple static server:

```bash
# using Python 3
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

---

## Project Structure

```
dice-duel/
├── images/           ← (if you have dice images)
├── index.html
├── dicee.html         ← (a secondary HTML in your repo)
├── styles.css
├── index.js
└── README.md
```

- **index.html** — the main entry page  
- **dicee.html** — an alternate page (script logic or demonstration)  
- **styles.css** — all CSS styles  
- **index.js** — game logic & DOM interaction  

---

## Usage

- When you open (or reload) the page, the dice roll automatically.  
- The result (Player 1 wins / Player 2 wins / Draw) appears at the top.  
- No buttons or actions required by the user.  

If you visit the alternate **dicee.html**, it may demonstrate the same or variant behavior (depending on code).  

---

## Customization

You can easily modify or extend this small project:

- Change the dice range (e.g. 1–20)  
- Add a “Roll Again” button instead of automatic reload  
- Display animations for dice rolling  
- Add sound effects  
- Keep history of past rolls and wins  
- Add player names, scoreboard, or multiple rounds  

The logic is simple and modular in JS, so adapting is straightforward.

---

## Contributing

Contributions are welcome! To improve this repo:

1. Fork the repository  
2. Create a new branch: `git checkout -b feature-your‑feature`  
3. Make your changes & commit them  
4. Push your branch and open a Pull Request  

Please keep changes focused, document them in code or comments, and make sure everything still works in vanilla contexts (i.e. no dependencies).

---

## License & Credits

This project is open source and can be used freely.  

**Author / Maintainer:** Yousef Ahmed  
**Repository:** https://github.com/yousefahmeddk/dice-duel  
**Live version:** https://yousefahmeddk.github.io/dice-duel/
