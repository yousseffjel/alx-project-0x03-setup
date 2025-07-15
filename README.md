# ALX Project 0x03 Setup

## Objective
Set up a base Next.js application demonstrating the DRY (Don't Repeat Yourself) framework for shared layouts across multiple pages. This project implements reusable Header and Footer components through a Layout wrapper component.

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/alx-project-0x03-setup.git
cd alx-project-0x03-setup
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Install required third-party dependency:
```bash
npm install react-icons
# or
yarn add react-icons
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## Project Structure

```
alx-project-0x03/
├── components/
│   ├── layouts/
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   └── Layout.tsx
│   └── common/
│       └── Button.tsx
├── pages/
├── public/
└── package.json
```

## Components

- **Header.tsx**: Navigation header component
- **Footer.tsx**: Site footer component  
- **Layout.tsx**: Wrapper component implementing DRY principle for shared layouts
- **Button.tsx**: Reusable button component

## Technologies Used

- Next.js (latest)
- React
- TypeScript
- React Icons (FA)

## License

This project is part of the ALX Software Engineering Program.