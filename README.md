# Abcproject                } else {

                    cout << key << " not found in the list." << endl;

                }

                break;

            case 8:

                obj.reverse();

                cout << "List reversed successfully." << endl;

                break;

            case 9:

                obj.traverse();

                break;

            case 10:

                cout << "Exiting...";

                break;

            default:

                cout << "Invalid choice. Please try again." << endl;

        }

    } while (choice != 10);

 

    return 0;

}
