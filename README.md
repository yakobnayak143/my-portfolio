<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Yakob | Full Stack Developer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, sans-serif;
        }

        body {
            background: #0f2027;
            background: linear-gradient(to right, #2c5364, #203a43, #0f2027);
            color: #fff;
        }

        header {
            text-align: center;
            padding: 60px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header h2 {
            font-weight: 300;
            color: #00eaff;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #00eaff;
        }

        section {
            max-width: 1000px;
            margin: auto;
            padding: 60px 20px;
        }

        .title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 40px;
            color: #00eaff;
        }

        .about {
            text-align: center;
            line-height: 1.8;
            font-size: 1.1rem;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            padding: 25px;
            border-radius: 12px;
            transition: transform 0.3s, background 0.3s;
        }

        .card:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.15);
        }

        .card h3 {
            margin-bottom: 10px;
            color: #00eaff;
        }

        .contact {
            text-align: center;
        }

        .contact p {
            margin: 10px 0;
            font-size: 1.1rem;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.3);
            margin-top: 40px;
        }

        footer span {
            color: #00eaff;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Yakob</h1>
    <h2>Aspiring Full Stack Developer</h2>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2 class="title">About Me</h2>
    <p class="about">
        Hello! I am <strong>Yakob</strong>, an enthusiastic and motivated learner who dreams of becoming a
        <strong>Full Stack Developer</strong>. I enjoy building beautiful websites and learning both frontend
        and backend technologies. My goal is to create impactful and user-friendly applications.
    </p>
</section>

<section id="skills">
    <h2 class="title">Skills</h2>
    <div class="skills">
        <div class="card">
            <h3>Frontend</h3>
            <p>HTML, CSS, JavaScript, Responsive Design</p>
        </div>
        <div class="card">
            <h3>Backend</h3>
            <p>Java, Python, Node.js (Learning)</p>
        </div>
        <div class="card">
            <h3>Database</h3>
            <p>MySQL, MongoDB (Basics)</p>
        </div>
        <div class="card">
            <h3>Tools</h3>
            <p>Git, GitHub, VS Code</p>
        </div>
    </div>
</section>

<section id="projects">
    <h2 class="title">Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>A personal responsive portfolio website using HTML and CSS.</p>
        </div>
        <div class="card">
            <h3>Student Management System</h3>
            <p>Basic CRUD application using Java and MySQL.</p>
        </div>
        <div class="card">
            <h3>Todo App</h3>
            <p>Simple todo application using HTML, CSS, and JavaScript.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="title">Contact</h2>
    <div class="contact">
        <p>Email: yakob@email.com</p>
        <p>Phone: +91 XXXXXXXXXX</p>
        <p>Location: India</p>
    </div>
</section>

<footer>
    <p>© 2026 <span>Yakob</span> | Full Stack Developer</p>
</footer>

</body>
</html>
