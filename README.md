# Landing Page Structure Cheatsheet

## Introduction

Welcome to Day 27 of the 100 days of web dev challenge! Today, I have created this cheat sheet to guide you on how to structure a landing page using HTML. This guide will help you understand the basic organization of a landing page and the HTML tags used for different sections.

## HTML Structure

A typical landing page structure includes several key sections. Below is a suggested HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page Title</title>
    <!-- Add your CSS link or styles here -->
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Your Brand Name or Logo</h1>
        <!-- Navigation Menu or Links -->
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <h2>Welcome to our Website</h2>
        <p>Your compelling and concise message goes here.</p>
        <!-- Call-to-Action (CTA) Button -->
        <button>Get Started</button>
    </section>

    <!-- Features Section -->
    <section id="features">
        <h2>Key Features</h2>
        <!-- Feature Cards or Descriptions -->
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <!-- Information about your company or team -->
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>What Our Customers Say</h2>
        <!-- Customer testimonials or reviews -->
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <!-- Contact Form or Details -->
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Your Company Name. All rights reserved.</p>
        <!-- Additional Footer Links or Information -->
    </footer>

</body>
</html>
```

## Explanation

1. **Header Section (`<header>`):** Contains the website's title, logo, and navigation links.

2. **Hero Section (`<section id="hero">`):** The main and often visually impactful section that introduces the key message of your landing page.

3. **Features Section (`<section id="features">`):** Highlights the key features or services your product or service offers.

4. **About Us Section (`<section id="about">`):** Provides information about your company, team, or organization.

5. **Testimonials Section (`<section id="testimonials">`):** Displays customer testimonials or reviews.

6. **Contact Section (`<section id="contact">`):** Includes a contact form or details for visitors to get in touch.

7. **Footer Section (`<footer>`):** Contains copyright information and additional links.

## Additional Tips

- Use meaningful `id` attributes for sections to enable easy navigation.
- Keep your HTML clean and semantic for better accessibility and SEO.

Feel free to customize this structure based on your specific needs. Happy coding!
