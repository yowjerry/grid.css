
# Gride.css

**Gride.css** is a lightweight CSS file that replicates the core features of the Bootstrap grid system. This file provides a flexible and responsive grid structure for your projects without needing the entire Bootstrap framework.

## Features

- **12-column grid system**: Supports up to 12 columns per row, just like Bootstrap.
- **Responsive design**: Automatically adjusts layout based on screen size (e.g., mobile, tablet, desktop).
- **Customizable gutters**: Easily adjust the spacing between columns using the `gutter` class.
- **Flexbox-based layout**: Ensures modern, consistent behavior across all supported browsers.
- **Utility classes**: Includes common utility classes for offsetting columns, hiding elements, and more.

## Getting Started

1. **Download** or **Clone** this repository.
2. Link the `gride.css` file in the `<head>` of your HTML:

   ```html
   <link rel="stylesheet" href="path/to/gride.css">
   ```

3. Use the grid system in your HTML just like you would with Bootstrap:

   ```html
   <div class="container">
       <div class="row">
           <div class="col-md-4">Column 1</div>
           <div class="col-md-4">Column 2</div>
           <div class="col-md-4">Column 3</div>
       </div>
   </div>
   ```

## Documentation

- **Grid Classes**:
  - `.container`: Wraps the grid and provides fixed-width or fluid layout options.
  - `.row`: Creates a horizontal group of columns.
  - `.col-[breakpoint]-[size]`: Defines the number of columns to span (e.g., `.col-md-4` for 4 out of 12 columns).

- **Responsive Breakpoints**:
  - `.col-xs` (extra small devices)
  - `.col-sm` (small devices)
  - `.col-md` (medium devices)
  - `.col-lg` (large devices)
  - `.col-xl` (extra large devices)

- **Utility Classes**:
  - `.offset-[breakpoint]-[size]`: Offsets columns.
  - `.hidden-[breakpoint]`: Hides elements at specified breakpoints.
  - `.gutter`: Adjusts spacing between columns.

## Customization

Feel free to modify `gride.css` to fit your specific needs. You can customize column widths, breakpoints, and gutter sizes directly in the CSS file.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

Inspired by the Bootstrap grid system.
