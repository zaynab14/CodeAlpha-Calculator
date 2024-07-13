## Calculator 

### Overview

This project is a simple calculator built with HTML, CSS, and JavaScript. It includes features like basic arithmetic operations, a clear function, and backspace functionality. The calculator also supports a dark and light theme toggle.

### Features

- **Basic Operations**: Addition, subtraction, multiplication, and division.
- **Clear and Backspace**: Clear the current input or remove the last digit.
- **Percentage Calculation**: Calculate the percentage of a number.
- **Responsive Design**: The calculator is responsive and works on various device sizes.
- **Dark/Light Theme Toggle**: Switch between dark and light themes.

### Technologies Used

- HTML
- CSS
- JavaScript

### Dependencies

- Font Awesome: Included via a CDN link in the `index.html` file for icons.
- Google Fonts: Poppins font is used and included via a CDN link in the `StyleCal.css` file.

### Customization

- **Theme Colors**:
  - Update the CSS variables in the `:root` selector and `html[data-theme="dark"]` in the `StyleCal.css` file to change theme colors.
- **Button Layout**:
  - Modify the button elements and their IDs in the `index.html` file to change the layout or add new buttons.

### Code Explanation

#### HTML (index.html)

- The structure consists of a heading section with a theme toggle, a result display area, and a keyboard section with number and operator buttons.
- Each button has an ID that corresponds to its value or function.

#### CSS (StyleCal.css)

- Custom properties (CSS variables) are used for theming and making it easy to switch between dark and light modes.
- Styles are defined for layout, button states, and responsiveness.

#### JavaScript (main.js)

- Event listeners are added to the theme toggle, number buttons, and operator buttons.
- Functions are defined to handle calculator operations, format numbers, and update the display.
