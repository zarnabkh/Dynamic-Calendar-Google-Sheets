# Dynamic Calendar with Writing Pad

## Overview
The Dynamic Calendar is a sophisticated tool designed in Google Sheets that integrates a calendar and a writing pad for daily task management. It efficiently handles task entries and updates the calendar view dynamically based on user interactions.

## Features
- **Dynamic Date Adjustment**: Initiate by double-clicking the start date (currently set to May 3); all dates adjust accordingly.
- **Task Management**: Supports adding up to six tasks per day directly via a dedicated notes section.
- **Automated Data Insertion**: Utilizes Google Sheets functions like ARRAY, IF, and LOGIC to automatically populate the calendar with tasks based on the specified date.
- **Error Handling**: Implements error checking to ensure smooth operation and user experience.

## How to Use
1. **Change the Date**: Double-click on the first date to change it. The entire calendar will update to reflect the new month or day sequence.
2. **Add Tasks**: Enter tasks in the writing pad section next to the desired date. Tasks are automatically placed into the calendar on the specified dates.

## Technical Details
This calendar uses a combination of Google Sheets formulas, including:
- **Data Validation**: Ensures that all entries are within acceptable parameters.
- **Array Formulas**: Facilitate the expansion of data across multiple cells automatically.
- **Logical Operations**: Check conditions and populate the calendar accordingly.

## Getting Started
To use this calendar, [make a copy](https://tinyurl.com/yvymuzvu) of the Google Sheet into your own Google Drive. This allows you to have a personal version that can be customized and used daily.

## Contributing
Contributions to enhance or expand the Dynamic Calendar's capabilities are welcome. Feel free to fork the project, make your changes, and submit a pull request with a description of enhancements.

## License
This project is released under the MIT License.
