# Plotly Dash Chart Gallery

An interactive web application showcasing various types of charts and visualizations using Plotly Dash. The application includes a comprehensive gallery of chart types with live examples, code snippets, and documentation references.

## Features

- Interactive chart selection
- Live visualization updates
- Code examples for each chart type
- Documentation references
- Parameter descriptions
- Use case explanations

## Chart Types Supported

- Line Charts
- Bar Charts
- Scatter Plots
- Histograms
- Box Plots
- Violin Plots
- Pie Charts
- Heatmaps
- Density Contours
- Sunburst Charts
- Strip Charts
- Polar Charts
- Funnel Charts
- Treemaps
- Parallel Coordinates
- Area Charts
- Candlestick Charts
- Choropleth Maps
- Scatter Maps

## Setup

### Local Development

1. Clone the repository
2. Create a virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python examples.py
   ```
5. Open your browser and navigate to `http://localhost:8002`

### Docker Setup

1. Build the Docker image:
   ```bash
   docker build -t dash-app .
   ```
2. Run the container:
   ```bash
   docker run -p 8002:8002 dash-app
   ```
3. Access the application at `http://localhost:8002`

## Dependencies

- dash==2.18.2
- Flask==3.0.3
- plotly==6.0.0
- pandas
- numpy
- waitress

## Usage

1. Select a chart type from the left sidebar
2. View the live chart example
3. Check the code snippet to learn how to create the chart
4. Review parameters and use cases in the reference section
5. Use the provided documentation links for detailed information

## Contributing

Feel free to open issues or submit pull requests for improvements or bug fixes.

## License

MIT License 