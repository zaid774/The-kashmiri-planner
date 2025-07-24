<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Apply Inter font family globally */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <!-- Header Section -->
    <header class="bg-white shadow-sm py-4 px-6 md:px-8 lg:px-12 rounded-b-lg">
        <nav class="container mx-auto flex justify-between items-center">
            <!-- Logo/Site Title -->
            <a href="#" class="text-2xl font-bold text-indigo-600 rounded-md p-2 hover:bg-indigo-50 transition-colors duration-200">
                MySite
            </a>

            <!-- Navigation Links (Hidden on small screens, could be a hamburger menu) -->
            <div class="hidden md:flex space-x-6">
                <a href="#" class="text-gray-700 hover:text-indigo-600 font-medium transition-colors duration-200 rounded-md p-2">Home</a>
                <a href="#" class="text-gray-700 hover:text-indigo-600 font-medium transition-colors duration-200 rounded-md p-2">Features</a>
                <a href="#" class="text-gray-700 hover:text-indigo-600 font-medium transition-colors duration-200 rounded-md p-2">About Us</a>
                <a href="#" class="text-gray-700 hover:text-indigo-600 font-medium transition-colors duration-200 rounded-md p-2">Contact</a>
            </div>

            <!-- Mobile Menu Button (Placeholder - functionality not implemented) -->
            <button class="md:hidden p-2 rounded-md text-gray-600 hover:bg-gray-200 transition-colors duration-200">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-indigo-500 to-purple-600 text-white py-16 md:py-24 px-6 md:px-8 lg:px-12 text-center rounded-lg m-4">
        <div class="container mx-auto max-w-3xl">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold leading-tight mb-6">
                Welcome to Our Amazing Platform
            </h1>
            <p class="text-lg md:text-xl mb-8 opacity-90">
                Discover innovative solutions and elevate your experience with our cutting-edge services.
            </p>
            <button class="bg-white text-indigo-600 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-indigo-50 hover:scale-105 transition-all duration-300 ease-in-out focus:outline-none focus:ring-4 focus:ring-white focus:ring-opacity-50">
                Get Started Now
            </button>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-12 md:py-16 px-6 md:px-8 lg:px-12">
        <div class="container mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-10 text-gray-900">Our Core Features</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature Card 1 -->
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition-shadow duration-300 flex flex-col items-center text-center">
                    <div class="bg-indigo-100 text-indigo-600 p-4 rounded-full mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h4l1-1 1-6h5m-1-10L17 5m-12 1h16a1 1 0 011 1v8a1 1 0 01-1 1H5a1 1 0 01-1-1V7a1 1 0 011-1z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Seamless Integration</h3>
                    <p class="text-gray-600">
                        Easily connect with your existing tools and workflows for a smooth experience.
                    </p>
                </div>

                <!-- Feature Card 2 -->
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition-shadow duration-300 flex flex-col items-center text-center">
                    <div class="bg-green-100 text-green-600 p-4 rounded-full mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Blazing Fast Performance</h3>
                    <p class="text-gray-600">
                        Experience lightning-fast speeds and optimal efficiency with our optimized infrastructure.
                    </p>
                </div>

                <!-- Feature Card 3 -->
                <div class="bg-white p-6 rounded-xl shadow-md hover:shadow-lg transition-shadow duration-300 flex flex-col items-center text-center">
                    <div class="bg-yellow-100 text-yellow-600 p-4 rounded-full mb-4">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">24/7 Customer Support</h3>
                    <p class="text-gray-600">
                        Our dedicated support team is always ready to assist you, day or night.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section class="bg-indigo-700 text-white py-12 md:py-16 px-6 md:px-8 lg:px-12 text-center rounded-lg m-4">
        <div class="container mx-auto max-w-3xl">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to Get Started?</h2>
            <p class="text-lg md:text-xl mb-8 opacity-90">
                Join thousands of satisfied users today and transform your online presence.
            </p>
            <button class="bg-white text-indigo-700 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-indigo-100 hover:scale-105 transition-all duration-300 ease-in-out focus:outline-none focus:ring-4 focus:ring-white focus:ring-opacity-50">
                Sign Up For Free
            </button>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-gray-300 py-8 px-6 md:px-8 lg:px-12 rounded-t-lg">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center text-center md:text-left">
            <p class="mb-4 md:mb-0">&copy; 2025 MySite. All rights reserved.</p>
            <div class="flex space-x-6">
                <a href="#" class="hover:text-white transition-colors duration-200">Privacy Policy</a>
                <a href="#" class="hover:text-white transition-colors duration-200">Terms of Service</a>
            </div>
        </div>
    </footer>

</body>
</html>
