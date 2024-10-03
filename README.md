# Kategna

**Kategna** is a web application designed to offer users a seamless experience in interacting with various types of Ethiopian cuisine, primarily focusing on providing detailed information and resources related to traditional dishes. It serves as an online platform for users who want to explore, learn, and engage with Ethiopian culture through food.

## Objective

The main objective of Kategna is to bring Ethiopian culinary heritage to the digital space. It helps users discover traditional recipes, explore regional dishes, and learn more about the rich food culture of Ethiopia. Kategna aims to:

- **Promote Ethiopian Cuisine**: Showcase a variety of Ethiopian dishes, both well-known and lesser-known, with rich information about their history, ingredients, and preparation.
- **Educate Users**: Provide step-by-step recipes, cooking tips, and cultural insights for those interested in making Ethiopian dishes at home.
- **Connect Food Enthusiasts**: Act as a hub for people who want to share their love of food, exchange recipes, and discuss culinary techniques.

## Features

- **Recipe Listings**: Users can browse through a wide selection of traditional Ethiopian recipes. Each recipe comes with detailed instructions, ingredient lists, and preparation tips.
- **Cultural Insights**: Each dish is accompanied by cultural notes, explaining its significance in Ethiopian society and its place in specific regions.
- **Search Functionality**: A robust search system allows users to quickly find recipes based on ingredients, cooking methods, or specific dish names.
- **Responsive Layout**: The application is optimized for mobile, tablet, and desktop use, ensuring a seamless experience on any device.
- **High-Quality Images**: The `img/` directory contains high-resolution images of the dishes, offering users a visual preview of each recipe.
  
## How it Works

1. **User Interaction**: Users arrive at the homepage (`index.html`), where they are greeted with a curated list of traditional Ethiopian dishes. They can navigate through different sections or use the search feature to find specific recipes.
2. **Recipe Details**: Clicking on a dish opens up a detailed page that provides instructions on how to prepare the dish, along with its cultural background and tips for perfecting it.
3. **Mobile-Friendly Interface**: Kategna ensures that users on all devices have access to the full functionality, from browsing recipes to reading articles about Ethiopian food culture.

## Project Structure

```plaintext
Kategna/
│
├── css/
│   └── [All stylesheets go here, handling the layout and visual aesthetics of the app]
│
├── img/
│   └── [Images of dishes, used for visual representation of the recipes]
│
├── js/
│   └── [JavaScript files that handle interactivity, search functionality, and UI behaviors]
│
└── index.html
    └── [Main entry point where users land. Displays an overview of the application and features key recipes]
```

### CSS
The design of the website is maintained through the CSS files stored in the `css` folder. The layout is responsive and adaptable to different screen sizes.

### JavaScript
JavaScript is used to manage interactivity, such as the search functionality and dish navigation. It enhances the user experience by dynamically updating content without needing full page reloads.

### HTML
The `index.html` is the homepage, serving as the primary interface where users interact with the recipes. Additional pages for each recipe may be linked from this file.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/kategna.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd kategna
   ```
3. **Open the project**:
   Open `index.html` in a browser to view the web app.

## Future Enhancements

- **User Accounts**: Allow users to create profiles where they can save favorite recipes and share their own.
- **Recipe Rating**: Implement a system where users can rate and comment on recipes.
- **Shopping List Generator**: Enable users to automatically generate shopping lists based on selected recipes.

## License

This project is licensed under the MIT License.

