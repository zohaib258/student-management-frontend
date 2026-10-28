This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
# Student Management System — Frontend

A web-based Student Management System frontend built with Next.js, React, and TypeScript. It provides separate interfaces for students and administrators.

## Technologies

- Next.js
- React
- TypeScript
- CSS
- REST API integration

## Features

- Student registration and login
- Student dashboard and profile management
- Password change functionality
- Admin login and registration
- Admin dashboard and student management

## Requirements

- Node.js and npm
- The Student Management System NestJS backend
- MySQL configured for the backend

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/zohaib258/student-management-frontend.git
cd student-management-frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a local environment file:

```bash
cp .env.example .env.local
```

The default configuration is:

```dotenv
NEXT_PUBLIC_API_BASE_URL=http://localhost:3002/api
```

Change this URL if your backend runs at a different address.

### 4. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

Make sure the NestJS backend is running on port 3002 and is configured to accept requests from the frontend origin.

## Available Scripts

| Command | Purpose |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the application |
| `npm start` | Start the production server |
| `npm run lint` | Run ESLint |

## Related Repository

Backend: https://github.com/zohaib258/student-management-backend

## Security

Do not commit `.env.local` or other files containing local credentials or secrets. Use `.env.example` as the configuration template.

