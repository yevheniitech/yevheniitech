<div align="center">

<!-- Animated Banner -->
<svg width="1000" height="230" viewBox="0 0 1000 230" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="animated-bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0f172a">
        <animate attributeName="stop-color" values="#0f172a; #1e293b; #0f2b38; #0f172a" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#113e47">
        <animate attributeName="stop-color" values="#113e47; #164e63; #0e453a; #113e47" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <linearGradient id="text-gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38bdf8" />
      <stop offset="50%" stop-color="#34d399" />
      <stop offset="100%" stop-color="#38bdf8" />
      <animate attributeName="x1" values="0%; 100%; 0%" dur="6s" repeatCount="indefinite" />
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect x="0" y="0" width="1000" height="230" fill="url(#animated-bg)" rx="12" />

  <path d="M 0 190 Q 250 160, 500 190 T 1000 190 V 230 H 0 Z" fill="#38bdf8" opacity="0.15">
    <animate attributeName="d" 
             values="M 0 190 Q 250 160, 500 190 T 1000 190 V 230 H 0 Z;
                     M 0 180 Q 250 200, 500 180 T 1000 180 V 230 H 0 Z;
                     M 0 190 Q 250 160, 500 190 T 1000 190 V 230 H 0 Z" 
             dur="6s" repeatCount="indefinite" />
  </path>
  
  <path d="M 0 200 Q 250 220, 500 200 T 1000 200 V 230 H 0 Z" fill="#0f172a">
    <animate attributeName="d" 
             values="M 0 200 Q 250 220, 500 200 T 1000 200 V 230 H 0 Z;
                     M 0 205 Q 250 185, 500 205 T 1000 205 V 230 H 0 Z;
                     M 0 200 Q 250 220, 500 200 T 1000 200 V 230 H 0 Z" 
             dur="5s" repeatCount="indefinite" />
  </path>

  <text x="500" y="115" 
        font-family="system-ui, -apple-system, sans-serif" 
        font-weight="900" 
        font-size="48" 
        fill="url(#text-gradient)" 
        text-anchor="middle"
        letter-spacing="4"
        filter="url(#glow)">
    FULL STACK DEVELOPER
  </text>

  <text x="500" y="155" 
        font-family="system-ui, -apple-system, sans-serif" 
        font-weight="500" 
        font-size="18" 
        fill="#94a3b8" 
        text-anchor="middle"
        letter-spacing="2">
    yevheniitech | Senior Full-Stack &amp; Product Engineer
    <animate attributeName="opacity" values="0.6; 1; 0.6" dur="3s" repeatCount="indefinite" />
  </text>
</svg>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/your_telegram)

<p align="center">
  <b>Building scalable B2B platforms, cross-platform mobile apps, and real-time AI integrations for US & EU markets.</b>
</p>

</div>

---

### 🛠️ Tech Stack

#### 🎨 Front-End Development
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/Material_UI-007FFF?style=for-the-badge&logo=mui&logoColor=white" />
  <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" />
  <img src="https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white" />
</p>

#### ⚙️ Back-End Development
<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white" />
</p>

#### ☁️ DevOps & Cloud
<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
</p>

#### 📱 Mobile Development
<p align="left">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

---

### 🚀 Key Highlights & Impact

* **Fintech SaaS Optimization:** Re-architected Node.js API layers for an enterprise platform (~1k users), dropping server response latency by **35%**.
* **Mobile Product Launch:** Built and published a cross-platform React Native app from scratch, scaling it past **10,000+** active installs.
* **AI Pipelines & Async Queues:** Engineered production LLM integrations using Redis BullMQ for async background execution without freezing the UI.

---

### 📈 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=yevheniitech&show_icons=true&theme=dark" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yevheniitech&layout=compact&theme=dark" />

</div>

---

### 🎓 Education & Honors

* **Master’s Degree with Honors (Cum Laude)** — Lviv Polytechnic National University
* **Bachelor’s Degree with Honors (Cum Laude)** — Lviv Polytechnic National University
