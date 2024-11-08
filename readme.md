# SQL Bot with LangChain and Streamlit

This project demonstrates how to build a SQL bot using LangChain, Google Generative AI, and Streamlit for the user interface. The bot is designed to interact with a MySQL database and generate SQL queries based on user input.

## Features

- **LangChain Integration**: Utilizes LangChain for natural language processing and query generation.
- **Google Generative AI**: Employs ChatGoogleGenerativeAI for generating responses.
- **Semantic Similarity**: Uses HuggingFaceEmbeddings and Chroma for semantic similarity and example selection.
- **Streamlit UI**: Provides a user-friendly interface using Streamlit.

## Setup

1. **Clone the Repository**: 
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install Dependencies**: 
    Ensure you have Python installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Environment Variables**: 
    Create a `.env` file in the project root and add your environment variables:
    ```plaintext
    DB_USER=<your-database-username>
    DB_PASSWORD=<your-database-password>
    DB_HOST=<your-database-host>
    DB_NAME=<your-database-name>
    ```

4. **Run the Application**: 
    Start the Streamlit application:
    ```bash
    streamlit run app.py
    ```

## Usage

- **User Input**: Enter your natural language query in the Streamlit interface.
- **SQL Query Generation**: The bot generates a syntactically correct SQL query based on the input.
- **Result Display**: The results of the SQL query are displayed in the Streamlit interface.

## Components

- **LangChain**: For natural language processing and query generation.
- **Google Generative AI**: For generating responses.
- **HuggingFaceEmbeddings**: For semantic similarity.
- **Chroma**: For vector storage and retrieval.
- **Streamlit**: For the user interface.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- LangChain
- Google Generative AI
- HuggingFace
- Streamlit
