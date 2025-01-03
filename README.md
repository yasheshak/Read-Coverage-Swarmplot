# Swarm Plot Generator for Identity and Coverage Data

This script generates a swarm plot to visualize the relationship between identity percentages and subread coverage from given input files. It processes data, categorizes it into groups based on coverage ranges, and plots each group as a swarm plot with medians indicated.

## Features
- Reads identity and coverage data from input files.
- Groups data into four categories based on coverage ranges.
- Plots identity percentages as a swarm plot for each coverage range.
- Highlights the median for each group.
- Outputs a high-resolution PNG figure.

## Usage
### Input Files
- **Identity File** (`--identityFile`): Contains data mapping names to identity percentages.
- **Coverage File** (`--coverageFile`): Contains data mapping names to coverage values.

### Output
- **Output File** (`--outFile`): The filename for the generated plot (default: `identity_coverage_swarmplot.png`).

### Command-Line Arguments
```bash
python script_name.py -i <identity_file> -c <coverage_file> -o <output_file>
