# 🌌 Constellation Portfolio - Interactive Night Sky Theme

> **Turn your portfolio into a magical, interactive constellation.**  
> A unique, open-source personal website where every star tells a story.

<p align="center">
  <img src="preview.png" alt="Constellation Portfolio Preview" width="700"/>
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=Bq83ZkTeeao">
    <img src="https://img.shields.io/badge/Watch_Tutorial-red?style=for-the-badge&logo=youtube" alt="Watch Tutorial">
  </a>
  <a href="https://github.com/you-mountain/constellation-portfolio">
    <img src="https://img.shields.io/badge/Live_Demo-brightgreen?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://github.com/you-mountain/constellation-portfolio">
    <img src="https://img.shields.io/badge/Star_Repo-gold?style=for-the-badge&logo=github" alt="Star Repo">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
  <img src="https://img.shields.io/badge/HTML-100%25-orange.svg" alt="HTML">
  <img src="https://img.shields.io/badge/Zero_Dependencies-blue.svg" alt="Zero Dependencies">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome">
</p>

---

## ✨ The Story Behind This Project

Tired of boring, generic portfolio templates that all look the same? Me too.

I built this constellation portfolio because I wanted something different. Something that would make recruiters stop scrolling and say "Wow, I've never seen this before."

Instead of a traditional list of skills and experiences, every star in this night sky represents a different chapter of my professional journey. The lines connecting them show how everything fits together. It's not just a portfolio—it's my personal universe.

The entire project is built with pure HTML, CSS, and JavaScript. No React. No frameworks. No bloat. Just clean, vanilla code that anyone can understand and customize.

Want to see exactly how it was built? I made a complete step-by-step tutorial walking through every line of code.

**Watch the full tutorial:** [https://www.youtube.com/watch?v=Bq83ZkTeeao](https://www.youtube.com/watch?v=Bq83ZkTeeao)

---

## 🚀 Quick Links

| Resource | Link |
|---|---|
| Full Tutorial | [Watch on YouTube](https://www.youtube.com/watch?v=Bq83ZkTeeao) |
| Live Website | [View Demo](https://you-mountain.github.io/constellation-portfolio) |
| Source Code | [GitHub Repository](https://github.com/you-mountain/constellation-portfolio) |
| YouTube Channel | [Mountain](https://www.youtube.com/@mountain8474) |

---

## ✨ Features

- Interactive Star Map - Click on any star to reveal a different section
- Glassmorphism Design - Modern frosted glass UI with backdrop-filter
- Animated Night Sky - Dynamic background with hundreds of twinkling stars
- Connected Lines - Stars form a unique constellation network
- Particle Effects - Magical floating particles around modal cards
- Fully Responsive - Looks stunning on mobile, tablet and desktop
- Zero Dependencies - Pure HTML, CSS, and vanilla JavaScript
- Bilingual Support - English and Persian versions available
- Open Source - MIT licensed, free for everything
- Accessible - Keyboard navigation and screen reader friendly
- SEO Optimized - Semantic HTML and proper meta tags

---

## 🎮 How It Works

1. You see a beautiful night sky with stars
2. Each star represents a different portfolio section
3. Lines connect related stars together
4. Click a star and a glass card opens with details
5. Explore skills, projects, contact info and more
6. Close it and click another star

**Behind the scenes:**

- Canvas API draws the animated galaxy background
- CSS backdrop-filter creates the frosted glass effect
- JavaScript events handle all the interactivity
- An array of objects stores all your portfolio data
- Dynamic rendering updates content instantly

---

## 🚀 Quick Start

**Method 1: Clone and Open**

```bash
git clone https://github.com/you-mountain/constellation-portfolio.git
cd constellation-portfolio
open index.html
```
Method 2: Download as ZIP
Click the green Code button at the top of this page

Select Download ZIP from the dropdown menu

Extract the downloaded ZIP file to any folder on your computer

Open the extracted folder

Double-click index.html to open it in your browser

That's it! The constellation is now running on your computer

Method 3: Deploy to GitHub Pages (Free Hosting)
Fork this repository by clicking the Fork button at the top right

Go to your forked repository's Settings tab

Click on Pages in the left sidebar

Under Branch, select main from the dropdown

Click Save

Wait about 1 minute for deployment

Your site will be live at: https://yourusername.github.io/constellation-portfolio

Share this link with anyone to show off your constellation!

Method 4: Use as a Template
Click the green Use this template button at the top

Select Create a new repository

Name your repository (for example: my-portfolio)

Choose Public or Private

Click Create repository

Clone your new repository and start customizing

Your project is ready to make your own

🔧 Customization Guide
Step 1: Find the Stars Array
Open index.html in any code editor (VS Code, Notepad++, or even Notepad). Scroll down until you find the stars array. It looks like this:

javascript
// ==========================================
// 📌 EDIT YOUR INFORMATION HERE
// ==========================================
const stars = [
    // Your stars go here...
];
Step 2: Understand the Star Structure
Each star has these properties:

javascript
{
    id: 'about',                    // Unique ID for this star
    label: 'About Me',              // Text shown below the star
    x: 18, y: 28,                   // Position on screen (0 to 100%)
    connect: ['skills', 'contact'], // Which stars to connect with lines
    emoji: '🌌',                    // Emoji shown in the modal
    title: 'About Me',              // Title at the top of the modal
    content: `                      // HTML content inside the modal
        <span class="emoji-display">🌌</span>
        <p>Hey there! I'm <strong>Alex Morgan</strong></p>
        <p>Full-Stack Developer & UI Designer</p>
        <p>📍 San Francisco, CA</p>
    `
}
Step 3: Change Your Information
Edit the content for each star to match your own information:

About star: Change name, job title, and location

Skills star: Update the skill tags with your tech stack

Experience star: Add your real work history with dates

Projects star: Link to your actual projects

Contact star: Add your real email and social links

Blog star: Add your real articles or remove this star

Step 4: Adjust Star Positions
Change x and y values to move stars around:

text
x = 0   → far left side of screen
x = 25  → left side
x = 50  → center of screen
x = 75  → right side
x = 100 → far right side

y = 0   → top of screen
y = 25  → upper area
y = 50  → middle of screen
y = 75  → lower area
y = 100 → bottom of screen
Step 5: Create Your Constellation Pattern
Use the connect array to draw lines between stars:

javascript
// Connect to one star
connect: ['skills']

// Connect to multiple stars
connect: ['skills', 'projects', 'contact']

// No connections at all
connect: []
Step 6: Add or Remove Stars
To add a new star: Copy an existing star object and paste it into the array. Give it a unique id, set its label, choose a position with x and y, and add your content.

To remove a star: Delete its entire object from the array. Also remove its id from any other star's connect array.

Step 7: Save and Refresh
After making changes, save the file and refresh your browser. Your changes will appear immediately.

🎯 Default Star Map
text
                    ⚡ Skills (48%, 18%)
                        |
    🌌 About (18%, 28%) ──── 💼 Experience (78%, 22%)
           |                        |
    📝 Blog (28%, 62%) ──── 📡 Contact (58%, 68%) ──── 🚀 Projects (88%, 48%)
Star ID	Default Label	Position	Connected To	Emoji
about	About Me	18%, 28%	skills, contact	🌌
skills	Skills	48%, 18%	about, projects, experience	⚡
experience	Experience	78%, 22%	skills, projects	💼
projects	Projects	88%, 48%	skills, experience, contact	🚀
contact	Contact	58%, 68%	about, projects, blog	📡
blog	Blog	28%, 62%	contact, about	📝
🛠️ Tech Stack
Technology	Purpose
HTML5	Semantic structure and accessibility
CSS3	Glassmorphism, animations, responsive design
JavaScript (Vanilla)	Canvas API, DOM manipulation, events
Canvas API	Galaxy background and constellation lines
CSS Grid & Flexbox	Layout system
Why no frameworks?

⚡ Faster loading with no bundle to download

🎓 Easier to understand for beginners

🔧 Simpler customization

🌐 Better SEO since search engines read HTML directly

💪 Teaches fundamental web concepts

📦 Zero node_modules folder

📂 Project Structure
text
constellation-portfolio/
├── index.html              # English version (main file)
├── README.md               # This documentation
├── preview.png             # Project preview image
└── LICENSE                 # MIT License
That's it! Just one HTML file. No build tools, no dependencies, no complexity.

🎨 Color Scheme
Element	Color
Background	Deep Space (#050510)
Star Core	Bright Gold (#ffcc00)
Star Glow	Warm Orange (#ff9933)
Lines	Faded Gold
Modal Background	Frosted Glass
Title Text	Soft Gold (#ffeacc)
Body Text	Light Blue (#d0dcff)
Accent Links	Warm Gold (#ffcc88)
📱 Browser Support
Browser	Support
Google Chrome	✅ Full (version 90+)
Mozilla Firefox	✅ Full (version 88+)
Apple Safari	✅ Full (version 14+)
Microsoft Edge	✅ Full (version 90+)
Opera	✅ Full (version 76+)
iOS Safari	✅ Full (version 14+)
Android Chrome	✅ Full (version 90+)
🎯 Perfect For
🧑‍💻 Web Developers building their portfolio

🎨 Designers showcasing creative work

📝 Students applying for internships

💼 Freelancers attracting clients

🚀 Job Seekers getting noticed by tech companies

🎓 Bootcamp Graduates demonstrating skills

🌐 Content Creators building personal brand

💻 Agencies creating team member profiles

🤝 Contributing
I welcome contributions from everyone!

How to contribute:

Fork the repository

Create a new branch: git checkout -b feature/my-feature

Make your changes

Commit your changes: git commit -m "Add my feature"

Push to the branch: git push origin feature/my-feature

Open a Pull Request

Contribution ideas:

🎨 New color themes (sunset, ocean, aurora)

🌟 Additional star shapes (diamond, hexagon)

🌠 Shooting star animations

🔊 Sound effects on star click

🌍 More language translations

🖼️ Custom icon support

📱 PWA support for offline mode

🎵 Background music toggle

🔄 Theme switcher

📄 PDF export feature

Found a bug? Open an issue with:

What you were doing

What you expected to happen

What actually happened

Your browser and operating system

Screenshots if possible

📞 Connect With Me
Platform	Link
🎥 YouTube	Mountain
📂 GitHub	you-mountain
📺 Full Tutorial	Watch Video
🌐 This Project	Constellation Portfolio
📄 License
This project is licensed under the MIT License. This means you can:

✅ Use it for personal projects

✅ Use it for commercial projects

✅ Modify and customize it however you want

✅ Distribute your version

✅ Use it privately

The only requirement is keeping the copyright notice. See the LICENSE file for full details.

⭐ Support This Project
If this project helped you, please consider:

⭐ Star this repository on GitHub

🎥 Subscribe to my YouTube channel

📺 Watch the full tutorial

💬 Comment your constellation name on the video

🔄 Share this project with other developers

🐛 Report bugs or suggest features

🤝 Contribute code improvements

❓ Frequently Asked Questions
Q: Is this really free?
A: YES! The project is MIT licensed. You can use it for personal, educational, or commercial projects without paying anything.

Q: Do I need coding experience?
A: Basic HTML knowledge helps, but you can customize everything by just editing text. The tutorial video walks you through every step.

Q: Can I use this on my portfolio?
A: Absolutely! That's exactly what it's made for. Just customize the content and make it yours.

Q: Will it work on mobile?
A: Yes! The design is fully responsive and adapts beautifully to phones, tablets, and desktops.

Q: How do I change the colors?
A: Edit the CSS in the style section of index.html. Look for color values and gradients—they're all clearly marked.

Q: Can I add more than 6 stars?
A: Yes! Just add more objects to the stars array. You can have as many as you want.

Q: How do I deploy this for free?
A: Use GitHub Pages! Push to a GitHub repository, enable Pages in Settings, and your site goes live instantly. Full instructions are in the Getting Started section above.

Q: Can I remove the YouTube link?
A: Yes, you can edit or remove any content in the stars array to make it entirely your own.

Q: Does this work offline?
A: Yes! Since there are no external dependencies, the entire project works offline once downloaded.

<p align="center"> <br> <b>Made with ✨ and 🌌 by <a href="https://www.youtube.com/@mountain8474">Mountain</a></b> <br> <i>May your stars always shine bright!</i> <br><br> <a href="https://www.youtube.com/watch?v=Bq83ZkTeeao"> <img src="https://img.shields.io/badge/📺_Watch_Tutorial-red?style=for-the-badge&logo=youtube" alt="Watch Tutorial"> </a> <br><br> <sub>⭐ If you like this project, please consider giving it a star!</sub> </p> ```
