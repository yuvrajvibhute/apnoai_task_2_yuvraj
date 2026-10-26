# 🌟 ApnoAI Internship — Task 2: Modern React Profile Card

A modern glassmorphism profile card component built with **React 18** and pure CSS. Designed to mimic the 2026 UI aesthetics of platforms like Linear, Stripe, and Vercel. 

Runs in a **single standalone HTML file** with zero setup, zero build steps, and zero dependencies to install.

---

## 🚀 Live Demo & Deployment

- **Live Demo (Vercel):** *Deploy on Vercel to get your URL (e.g., `https://apnoai-task-2-yuvraj.vercel.app`)*
- **GitHub Repository:** [https://github.com/yuvrajvibhute/apnoai_task_2_yuvraj](https://github.com/yuvrajvibhute/apnoai_task_2_yuvraj)

---

## ✨ Features

- **🧩 Component-Driven Architecture**: Structured using clean, reusable React components (`ProfileCard`, `TypingText`, `SkillPill`, `SocialLink`).
- **📥 Props for Dynamic Customization**: All profile information (Name, Role, Bio, Skills, Avatar, Social Links) is passed via React `props`.
- **🔄 Dynamic State Management (`useState`)**:
  - **Dark / Light Mode Toggle**: Smoothly switches color themes and background gradients on the fly.
  - **Interactive Like Counter (+10 XP Bonus)**: Stateful heart button with animated like counter and toggle state.
- **✨ Typing Effect (`useEffect`)**: Live typewriter animation displaying the bio text letter-by-letter.
- **🎨 2026 Glassmorphism Aesthetic**:
  - Backdrop blur, frosted glass borders, and subtle inset highlights.
  - Animated floating gradient orbs and background shifts.
  - Continuous rotating gradient border around the avatar.
  - Pulsing green active status indicator.
  - Interactive hover animations on skill tags and social buttons.
- **⚡ Zero Build Tools Required**: Powered by React 18 UMD CDN and in-browser Babel compilation.

---

## 🛠️ Tech Stack

- **Core:** [React 18](https://react.dev/) (via unpkg CDN)
- **Compiler:** [Babel Standalone](https://babeljs.io/)
- **Styling:** Custom Vanilla CSS3 (CSS Variables, Flexbox, Glassmorphism, Keyframe Animations)
- **Typography:** [Inter font](https://fonts.google.com/specimen/Inter) from Google Fonts

---

## 📂 Project Structure

```
apnoai-task-2/
├── index.html        # Complete React application (single-file architecture)
└── README.md         # Project documentation and guide
```

---

## 🏃 Getting Started Locally

No `npm install` or node environment required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/yuvrajvibhute/apnoai_task_2_yuvraj.git
   ```
2. Navigate into the folder:
   ```bash
   cd apnoai_task_2_yuvraj
   ```
3. Open `index.html` in your favorite web browser (double-click or right-click -> Open with Chrome).

---

## 🧠 Core React Concepts Demonstrated

### 1. Props (Inputs to Components)
Props allow the component to remain generic and reusable. Example from `index.html`:
```jsx
<ProfileCard
  name="Yuvraj Vibhute"
  role="Full-Stack Developer · ApnoAI Intern"
  bio="Building delightful products at the intersection of design and code..."
  skills={["React", "TypeScript", "Node.js", "Figma", "Python"]}
  avatar="https://ui-avatars.com/api/?name=Yuvraj+Vibhute&background=7c3aed&color=fff&size=200"
  github="https://github.com/yuvrajvibhute"
  twitter="mailto:yuvrajvibhute2222@gmail.com"
  linkedin="https://www.linkedin.com/in/yuvraj-vibhute-43336a321"
  instagram="https://www.instagram.com/yuvrajvibhute22"
/>
```

### 2. State (Component Memory)
State enables the component to remember user interactions and re-render automatically:
```jsx
// Dark mode state
const [isDark, setIsDark] = useState(false);

// Like counter state (Bonus Feature)
const [likes, setLikes] = useState(0);
const [liked, setLiked] = useState(false);
```

---

## ☁️ Deployment on Vercel

1. Log in to [Vercel](https://vercel.com) using your GitHub account.
2. Click **"Add New"** → **"Project"**.
3. Import the `apnoai_task_2_yuvraj` repository.
4. Set **Framework Preset** to **"Other"**.
5. Click **"Deploy"**.

---

## 👤 Author

**Yuvraj Vibhute**
- GitHub: [@yuvrajvibhute](https://github.com/yuvrajvibhute)
- LinkedIn: [Yuvraj Vibhute](https://www.linkedin.com/in/yuvraj-vibhute-43336a321)
- Instagram: [@yuvrajvibhute22](https://www.instagram.com/yuvrajvibhute22)
- Email: [yuvrajvibhute2222@gmail.com](mailto:yuvrajvibhute2222@gmail.com)
