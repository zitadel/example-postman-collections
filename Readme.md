# Getting Started with ZITADEL Postman Collection

This guide will help you import the ZITADEL Test environment and collection into Postman Web Version, allowing you to quickly start making API requests to ZITADEL's services.

## Prerequisites

- A web browser compatible with the Postman Web Version.
- An active Postman account. If you do not have one, sign up at [Postman](https://postman.com).

## Importing the Environment and Collection

### Step 1: Access Postman Web

1. Open your web browser and navigate to [Postman Web Version](https://web.postman.co).
2. Log in with your Postman account credentials.

### Step 2: Import the Environment File

1. In the Postman workspace, look for the **Import** button at the top left corner and click on it.
2. In the Import window, you have multiple options to upload your file. You can drag and drop the `Test.postman_environment.json` file directly into this window, or click **Upload Files** and select the file from your file explorer.
3. After selecting the file, Postman will show you a preview of the import. Ensure the file type is recognized as **Environment**.
4. Click **Import** to add the environment to your Postman workspace.

### Step 3: Import the Collection File

1. Repeat the import process by clicking on the **Import** button again.
2. Drag and drop the `ZITADEL_TEST.postman_collection.json` file into the import window, or click **Upload Files** and select the file.
3. Ensure the file type is recognized as **Collection** in the import preview.
4. Click **Import** to add the collection to your workspace.

### Step 4: Selecting the Imported Environment

1. After importing, make sure to select the imported environment for use. You can do this by clicking on the environment dropdown located at the top right corner of the screen, next to the eye icon.
2. From the dropdown, select **Test** (or whatever name was given to your imported environment).

### Step 5: Making Requests

1. Expand the imported **ZITADEL_TEST** collection by clicking on it from the left sidebar.
2. You will see a list of available requests within the collection. Click on any request to open it.
3. With the request open and the environment selected, you can modify the request parameters as needed and click on **Send** to make the request.

## Additional Information

- **Environment Variables**: The imported environment contains predefined variables that the collection requests might use. You can view and modify these variables by clicking on the eye icon next to the environment dropdown and selecting **Edit** next to the active environment.
- **Running Collections**: You can run the entire collection or specific requests within it. This is useful for automated testing or exploring API functionalities.
- **Postman Documentation**: For more detailed instructions on using Postman, refer to the [official Postman Learning Center](https://learning.postman.com).
