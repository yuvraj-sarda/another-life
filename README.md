# AnotherLife

Ever wondered what it's really like to walk in someone else's shoes? AnotherLife lets you experience different lives, circumstances, and challenges through interactive decision-making games. 

**🎮 [Try it now at experience-another-life.vercel.app](https://experience-another-life.vercel.app)**

Considering a new career path? Curious about a different lifestyle? Play through authentic life experiences and gain deeper insight into the realities, challenges, and rewards of living another life.

## Who Is This For?

**🎯 Career Explorers** - Test drive different paths before making the leap  
**🧠 Students & Graduates** - Gain realistic insights into various careers  
**💡 Curious Minds** - Experience "what would it be like to be X?"  
**🤝 Empathy Builders** - Understand different life circumstances

## Technical Features

- **Multiple Game Scenarios**: Choose from different business simulations
- **URL-based Navigation**: Each game has its own URL for easy sharing and bookmarking
- **Persistent Game State**: Game progress is saved in session storage
- **Dynamic Decision System**: Choices affect multiple metrics (money, health, mental peace, etc.)
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Built with Tailwind CSS and shadcn/ui components

## Project Structure

```
src/
├── components/          # UI components for life experiences
│   ├── ui/                     # Design system components
│   ├── ScenarioCard.tsx        # Individual scenario display
│   ├── ScenarioOptionCard.tsx  # Choice options
│   ├── GameStats.tsx           # Life metrics display
│   ├── WelcomeScreen.tsx       # Experience introduction
│   └── ...
├── data/               # All the simulations go here
│   ├── fitflow/            # Solo founder journey
│   ├── restaurant/         # Restaurant owner experience
│   └── template/           # Template for new experiences
├── lib/                
│   ├── gameManager.ts  # Manages all life experiences
│   └── utils.ts
├── pages/              # Main application pages
│   ├── Games.tsx       # Experience browser
│   ├── Game.tsx        # Active experience player
│   └── ...
├── types/              # TypeScript definitions
└── hooks/              # Custom React hooks
```

## Quick Start

```bash
npm install && npm run dev
```

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed development setup and architecture.

## Future Vision

We're working on expanding AnotherLife with more diverse life experiences, including:
- Different socioeconomic backgrounds and family situations
- Various professional paths and career challenges  
- Cultural and geographic perspectives
- Life transitions and major decisions

*Interested in contributing ideas or feedback? Reach out through GitHub issues.*

## License

This project is licensed under the MIT License.
