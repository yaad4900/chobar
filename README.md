# chobar
this is my first repository
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automotive Website</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Automotive Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Home</h2>
        <p>Welcome to our automotive website. We offer the best cars and services in the industry.</p>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We are a leading automotive company with years of experience.</p>
    </section>
    <section id="services">
        <h2>Services</h2>
        <p>We offer a wide range of automotive services, including car sales, repairs, and maintenance.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Automotive Website. All rights reserved.</p>
    </footer>
    <script src="scripts/main.js"></script>
</body>
</html>
