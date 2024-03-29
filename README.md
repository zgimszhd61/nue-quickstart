## Getting Started with Nue.js

Nue.js is a new JavaScript framework that aims to provide a simple, flexible, and performant development experience for building web applications and websites. Here's a quickstart guide to help you get started with Nue.js:

### Installation

Nue.js can be installed using either Bun (recommended) or Node.js. Follow the instructions based on your preferred environment:

**Using Bun:**

```bash
bun install nuekit --global
```

**Using Node.js:**

```bash
pnpm install nuekit --global
```

Verify the installation by running:

```bash
nue --version
```

### Creating a New Project

To create a new Nue.js project, you can either start from scratch or use a template. To use a template, run the following command:

```bash
bun create nue@latest
```

This will prompt you to name your project directory and choose a template. For this quickstart guide, we'll select the "Simple app" template, which is a basic single-page application.

### Running the Development Server

Once you've created your project, navigate to the project directory and start the development server:

```bash
cd your-project-name
nue
```

This will start the development server at `http://localhost:8080`. Open this URL in your browser, and you should see your Nue.js application running.

### Understanding the Project Structure

The "Simple app" template comes with the following directory structure:

```
your-project-name/
├── app/
│   ├── components/
│   │   └── Counter.html
│   ├── pages/
│   │   └── index.html
│   └── app.css
├── index.html
└── package.json
```

- `app/components/`: This directory contains reusable components for your application.
- `app/pages/`: This directory contains the pages of your application.
- `app.css`: The global CSS file for your application.
- `index.html`: The entry point of your application.

### Editing Components and Pages

You can start editing the components and pages in their respective directories. Nue.js uses a file-based routing system, where each `.html` file in the `app/pages/` directory represents a route in your application.

For example, if you create a new file `app/pages/about.html`, it will be accessible at `http://localhost:8080/about`.

### Hot Module Replacement (HMR)

One of the key features of Nue.js is its built-in support for Hot Module Replacement (HMR). This means that when you make changes to your code, the changes will be automatically reflected in the browser without the need for a full page reload.

### Building for Production

When you're ready to deploy your application, you can build a production-ready version by running:

```bash
nue build
```

This will create a `dist/` directory containing the optimized and minified files for your application.

You can find more detailed documentation and examples on the official Nue.js website: https://nuejs.org/docs/

Citations:
[1] https://blog.logrocket.com/introducing-nue-js-svelte-alternative/
[2] https://nuejs.org/docs/
[3] https://news.ycombinator.com/item?id=37507419
[4] https://github.com/nuejs/nue
[5] https://nuejs.org/docs/tutorials/build-a-simple-blog.html
[6] https://www.youtube.com/watch?v=KHF4JdcF4JA
[7] https://www.linkedin.com/pulse/nuejs-azure-static-web-app-laszlo-coleman-elhec
[8] https://github.com/nuejs/nue/issues/85
