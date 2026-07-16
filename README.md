# Chatbot Project

A lightweight React + Vite chatbot web app with a simple conversational interface, message history, and instant bot replies.

## Features

- Clean chat UI for user and bot messages
- Preloaded sample conversation on startup
- Instant bot replies using the `supersimpledev` chatbot utility
- Auto-scrolling message list for ongoing conversations
- Responsive, component-based React structure

## Tech Stack

- **JavaScript (ES Modules)**
- **React 19**
- **Vite 6**
- **CSS3**
- **HTML5**
- **ESLint 9**

## Installation / Setup

### Prerequisites

- Node.js 18+ (recommended)
- npm 9+

### Steps

```bash
git clone https://github.com/xpriyanshu8/chatbot-project.git
cd chatbot-project
npm install
```

## Usage

### Start development server

```bash
npm run dev
```

Open the local URL shown in the terminal (typically `http://localhost:5173`).

### Build for production

```bash
npm run build
```

### Preview production build locally

```bash
npm run preview
```

### Lint the project

```bash
npm run lint
```

## Project Structure

```text
chatbot-project/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── ChatInput.jsx
│   │   ├── ChatMessage.jsx
│   │   └── ChatMessages.jsx
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

## Configuration / Environment Variables

This project currently does **not** require any environment variables for local development.

If you add API keys or backend endpoints later, create a `.env` file and use Vite-prefixed variables (for example: `VITE_API_URL=...`).

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run lint/build checks
5. Open a pull request

## License

No license file is currently present in this repository.

If you plan to distribute or accept outside contributions, consider adding a license (for example, MIT) and updating this section.
