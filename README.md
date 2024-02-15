# Full Page Component

This project implements a full-page component with an image background, a translucent overlay, a centered title, and a button that triggers an alert when clicked. The component is designed to be responsive and work on all screen sizes.

## Project Structure

- `index.html`: Contains the HTML structure for the full-page component.
- `styles.css`: Defines the styles for the component, including layout, positioning, and responsiveness.
- `script.js`: Implements functionality for the button click event to trigger an alert.

## Usage

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser to view the full-page component.
3. Click on the "Click here" button to trigger the alert.

## Notes

- The HTML structure consists of a container div with a full-page image, an overlay, and content (title and button).

- The CSS ensures the image covers the entire viewport, adds a translucent overlay, and centers the content vertically and horizontally. It also sets overflow: hidden; on the body and HTML to prevent any potential small white space at the bottom of the page.

- The JavaScript adds an event listener to the button to display an alert when clicked.

- The image needs to be provided by the FE engineer and referenced in the HTML src attribute.

- CSS properties like object-fit: cover ensure the image is optimized for different screen sizes.

- The overlay's transparency can be adjusted by modifying the RGBA value in the CSS.

- This solution utilizes modern CSS features and native JavaScript for simplicity and efficiency. It assumes the usage of the latest native browser features and APIs, without worrying about cross-browser compatibility.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
