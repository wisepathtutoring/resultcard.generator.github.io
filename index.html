<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Result Card Generator</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Custom styles for the app */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f4f8; /* Light blue-gray background */
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 2rem;
            box-sizing: border-box;
        }
        .container {
            background-color: #ffffff;
            border-radius: 1rem; /* More rounded corners */
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); /* Softer shadow */
            padding: 2.5rem;
            width: 100%;
            max-width: 900px; /* Max width for larger screens */
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        .input-group {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
        .input-group label {
            font-weight: 600;
            color: #334155; /* Darker text for labels */
        }
        .input-group input[type="text"],
        .input-group input[type="email"], /* Added email type */
        .input-group input[type="number"],
        .input-group input[type="file"],
        .input-group select { /* Added select for styling */
            padding: 0.75rem 1rem;
            border: 1px solid #cbd5e1; /* Lighter border */
            border-radius: 0.5rem; /* Rounded input fields */
            font-size: 1rem;
            transition: border-color 0.2s;
        }
        .input-group input[type="text"]:focus,
        .input-group input[type="email"]:focus, /* Added email type */
        .input-group input[type="number"]:focus,
        .input-group input[type="file"]:focus,
        .input-group select:focus {
            outline: none;
            border-color: #3b82f6; /* Blue focus border */
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.25); /* Focus ring */
        }
        /* Style for highlighted empty fields */
        .input-group input.border-red-500,
        .input-group select.border-red-500 {
            border-color: #ef4444; /* Tailwind red-500 */
            background-color: #fef2f2; /* Tailwind red-50 */
        }
        .btn-primary {
            background-color: #4f46e5; /* Deeper violet */
            color: #ffffff;
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem; /* Rounded button */
            font-weight: 700;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
            box-shadow: 0 4px 10px rgba(79, 70, 229, 0.2); /* Button shadow */
        }
        .btn-primary:hover {
            background-color: #4338ca; /* Darker violet on hover */
            transform: translateY(-1px);
        }
        .btn-secondary {
            background-color: #64748b; /* Gray for print button */
            color: #ffffff;
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem;
            font-weight: 700;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
            box-shadow: 0 4px 10px rgba(100, 116, 139, 0.2);
        }
        .btn-secondary:hover {
            background-color: #475569;
            transform: translateY(-1px);
        }
        .btn-success { /* Added for Send Email button */
            background-color: #22c55e; /* Tailwind green-500 */
            color: #ffffff;
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem;
            font-weight: 700;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
            box-shadow: 0 4px 10px rgba(34, 197, 94, 0.2);
        }
        .btn-success:hover {
            background-color: #16a34a; /* Darker green on hover */
            transform: translateY(-1px);
        }
        .btn-info { /* Added for WhatsApp link button */
            background-color: #3b82f6; /* Tailwind blue-500 */
            color: #ffffff;
            padding: 0.75rem 1.5rem;
            border-radius: 0.75rem;
            font-weight: 700;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
            box-shadow: 0 4px 10px rgba(59, 130, 246, 0.2);
        }
        .btn-info:hover {
            background-color: #2563eb; /* Darker blue on hover */
            transform: translateY(-1px);
        }


        .result-card {
            border: 2px solid #e2e8f0; /* Light border for card */
            border-radius: 0.75rem;
            padding: 2rem;
            margin-top: 2rem;
            background-color: #f8fafc; /* Very light background for result */
            background-size: cover; /* Cover the entire area */
            background-repeat: no-repeat; /* Do not repeat the image */
            background-position: center; /* Center the background image */
        }
        .subject-input-row {
            display: grid;
            grid-template-columns: 1fr 0.5fr 0.5fr; /* Subject, Total, Obtained */
            gap: 1rem;
            align-items: center;
        }
        @media (max-width: 768px) {
            .container {
                padding: 1.5rem;
            }
            .subject-input-row {
                grid-template-columns: 1fr; /* Stack on small screens */
            }
            .subject-input-row > div {
                width: 100%;
            }
        }

        /* Print Specific Styles */
        @media print {
            body {
                background-color: #ffffff;
                padding: 0;
                margin: 0;
            }
            .container {
                box-shadow: none;
                border: none;
                padding: 1rem;
                max-width: none;
                width: auto;
            }
            #inputForm, #resultControls, #csvUploadSection, #sendEmailSection, #whatsappSection { /* Hide email/whatsapp section during print */
                display: none;
            }
            .result-card {
                border: none;
                box-shadow: none;
                padding: 0;
                margin: 0;
                /* Print background images if browser settings allow */
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            .signature-image {
                max-width: 100px; /* Adjust size for print */
                height: auto;
            }
        }
    </style>
</head>
<body class="selection:bg-violet-200 selection:text-violet-900">
    <div class="container">
        <h1 class="text-3xl font-bold text-center text-gray-800 mb-6">School Result Card Generator</h1>

        <!-- Input Form Section -->
        <div id="inputForm" class="bg-blue-50 p-6 rounded-xl shadow-inner">
            <h2 class="text-2xl font-semibold text-gray-700 mb-5">Upload Assets & Data</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-4 mb-8">
                <div class="input-group">
                    <label for="schoolLogoUpload">School Logo (PNG/JPG):</label>
                    <input type="file" id="schoolLogoUpload" accept="image/png, image/jpeg" class="w-full">
                </div>
                <div class="input-group">
                    <label for="principalSignatureUpload">Principal Signature (PNG/JPG):</label>
                    <input type="file" id="principalSignatureUpload" accept="image/png, image/jpeg" class="w-full">
                </div>
                <div class="input-group">
                    <label for="classTeacherSignatureUpload">Class Teacher Signature (PNG/JPG):</label>
                    <input type="file" id="classTeacherSignatureUpload" accept="image/png, image/jpeg" class="w-full">
                </div>
                <div class="input-group">
                    <label for="resultBackgroundUpload">Result Card Background Image (PNG/JPG):</label>
                    <input type="file" id="resultBackgroundUpload" accept="image/png, image/jpeg" class="w-full">
                </div>
            </div>

            <div id="csvUploadSection" class="bg-yellow-50 p-6 rounded-xl shadow-inner mb-8">
                <h2 class="text-2xl font-semibold text-gray-700 mb-5">Load Data from CSV File (Optional)</h2>
                <p class="text-sm text-gray-600 mb-4">
                    To load student and marks data from a CSV file, ensure it follows this exact header format (case-sensitive): <br>
                    `Student Name,Father's Name,Roll No,Class,English,Mathematics,Science,Urdu,Islamiyat,Arabic,Computer,Social Studies,History,Taleem ul Quran`
                    <br> *Only enter obtained marks for subjects.* Empty subject columns in CSV will be ignored.
                    <br><br>
                    <a href="https://docs.google.com/spreadsheets/d/15i5rbgSaznMCaVcTg49Bg3nbCz_uCt2KTSJH4jPKYnY/edit?usp=sharing" target="_blank" class="text-blue-600 hover:underline font-semibold">Click here for an example Google Spreadsheet format</a>
                </p>
                <div class="input-group mb-4">
                    <label for="csvFileUpload">Upload CSV File:</label>
                    <input type="file" id="csvFileUpload" accept=".csv" class="w-full">
                </div>
                <button id="loadCsvBtn" class="btn-primary w-full bg-green-600 hover:bg-green-700">Load Data from CSV</button>
            </div>

            <h2 class="text-2xl font-semibold text-gray-700 mb-5">School & Student Information</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-4 mb-8">
                <div class="input-group">
                    <label for="schoolNameInput">School Name:</label>
                    <input type="text" id="schoolNameInput" placeholder="Enter school's name (e.g., Elite Scholars Academy)" class="w-full">
                </div>
                <div class="input-group">
                    <label for="schoolAddressInput">School Address:</label>
                    <input type="text" id="schoolAddressInput" placeholder="Enter school's address (e.g., 123 Education Lane, Learning City)" class="w-full">
                </div>
                <div class="input-group">
                    <label for="examTypeInput">Exam Type:</label>
                    <select id="examTypeInput" class="w-full">
                        <option value="Annual">Annual Examination</option>
                        <option value="Semester 1">Semester 1 Examination</option>
                        <option value="Semester 2">Semester 2 Examination</option>
                        <option value="Mid-Term">Mid-Term Examination</option>
                    </select>
                </div>
                <div class="input-group">
                    <label for="sessionInput">Session / Batch:</label>
                    <input type="text" id="sessionInput" placeholder="e.g., 2024-2025" class="w-full" value="2024-2025">
                </div>
                <div class="input-group">
                    <label for="studentName">Student Name:</label>
                    <input type="text" id="studentName" placeholder="Enter student's full name" class="w-full">
                </div>
                <div class="input-group">
                    <label for="fatherName">Father's Name:</label>
                    <input type="text" id="fatherName" placeholder="Enter father's full name" class="w-full">
                </div>
                <div class="input-group">
                    <label for="rollNo">Roll No:</label>
                    <input type="text" id="rollNo" placeholder="e.g., 12345" class="w-full">
                </div>
                <div class="input-group">
                    <label for="class">Class:</label>
                    <input type="text" id="class" placeholder="e.g., 10th Grade" class="w-full">
                </div>
            </div>

            <h2 class="text-2xl font-semibold text-gray-700 mb-2">Subject Marks</h2>
            <p class="text-sm text-gray-600 mb-4">
                Enter obtained marks for applicable subjects. Leave blank if a subject is not applicable for this student/grade.
            </p>
            <div id="subjectsContainer" class="flex flex-col gap-4 mb-8">
                <!-- Subject Input Fields -->
                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="eng">
                    <div class="input-group">
                        <label for="subjectName_eng">Subject Name:</label>
                        <input type="text" id="subjectName_eng" value="English" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_eng">Total Marks:</label>
                        <select id="totalMarks_eng" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_eng">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_eng" placeholder="e.g., 85" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="math">
                    <div class="input-group">
                        <label for="subjectName_math">Subject Name:</label>
                        <input type="text" id="subjectName_math" value="Mathematics" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_math">Total Marks:</label>
                        <select id="totalMarks_math" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_math">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_math" placeholder="e.g., 92" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="sci">
                    <div class="input-group">
                        <label for="subjectName_sci">Subject Name:</label>
                        <input type="text" id="subjectName_sci" value="Science" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_sci">Total Marks:</label>
                        <select id="totalMarks_sci" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_sci">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_sci" placeholder="e.g., 78" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="urdu">
                    <div class="input-group">
                        <label for="subjectName_urdu">Subject Name:</label>
                        <input type="text" id="subjectName_urdu" value="Urdu" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_urdu">Total Marks:</label>
                        <select id="totalMarks_urdu" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_urdu">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_urdu" placeholder="e.g., 90" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="isl">
                    <div class="input-group">
                        <label for="subjectName_isl">Subject Name:</label>
                        <input type="text" id="subjectName_isl" value="Islamiyat" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_isl">Total Marks:</label>
                        <select id="totalMarks_isl" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_isl">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_isl" placeholder="e.g., 95" min="0" max="150" class="w-full">
                    </div>
                </div>

                <!-- New Subjects Added -->
                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="arabic">
                    <div class="input-group">
                        <label for="subjectName_arabic">Subject Name:</label>
                        <input type="text" id="subjectName_arabic" value="Arabic" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_arabic">Total Marks:</label>
                        <select id="totalMarks_arabic" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_arabic">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_arabic" placeholder="e.g., 70 (optional)" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="computer">
                    <div class="input-group">
                        <label for="subjectName_computer">Subject Name:</label>
                        <input type="text" id="subjectName_computer" value="Computer" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_computer">Total Marks:</label>
                        <select id="totalMarks_computer" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_computer">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_computer" placeholder="e.g., 88 (optional)" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="social_studies">
                    <div class="input-group">
                        <label for="subjectName_social_studies">Subject Name:</label>
                        <input type="text" id="subjectName_social_studies" value="Social Studies/Pak Studies" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_social_studies">Total Marks:</label>
                        <select id="totalMarks_social_studies" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_social_studies">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_social_studies" placeholder="e.g., 75 (optional)" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="history">
                    <div class="input-group">
                        <label for="subjectName_history">Subject Name:</label>
                        <input type="text" id="subjectName_history" value="History" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_history">Total Marks:</label>
                        <select id="totalMarks_history" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_history">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_history" placeholder="e.g., 65 (optional)" min="0" max="150" class="w-full">
                    </div>
                </div>

                <div class="subject-input-row items-center p-4 bg-gray-50 rounded-lg shadow-sm" data-subject-id="taleem_ul_quran">
                    <div class="input-group">
                        <label for="subjectName_taleem_ul_quran">Subject Name:</label>
                        <input type="text" id="subjectName_taleem_ul_quran" value="Taleem ul Quran" class="w-full font-medium" disabled>
                    </div>
                    <div class="input-group">
                        <label for="totalMarks_taleem_ul_quran">Total Marks:</label>
                        <select id="totalMarks_taleem_ul_quran" class="w-full">
                            <option value="100">100</option>
                            <option value="150">150</option>
                            <option value="75">75</option>
                            <option value="50">50</option>
                        </select>
                    </div>
                    <div class="input-group">
                        <label for="obtainedMarks_taleem_ul_quran">Obtained Marks:</label>
                        <input type="number" id="obtainedMarks_taleem_ul_quran" placeholder="e.g., 98 (optional)" min="0" max="150" class="w-full">
                    </div>
                </div>
            </div>

            <button id="generateResultBtn" class="btn-primary w-full">Generate Result Card</button>
        </div>

        <!-- Result Card Display Section -->
        <div id="resultCardDisplay" class="result-card hidden">
            <div class="text-center mb-6">
                <img id="displaySchoolLogo" src="https://placehold.co/100x100/A0D468/ffffff?text=School+Logo" alt="School Logo" class="mx-auto mb-3 rounded-full shadow-md w-24 h-24 object-contain">
                <h2 class="text-3xl font-bold text-gray-900" id="displaySchoolName">Elite Scholars Academy</h2>
                <p class="text-md text-gray-600" id="displayExamType">Annual Examination Result</p>
                <p class="text-md text-gray-600" id="displaySession">Session 2024-2025</p>
                <p class="text-sm text-gray-500 mt-1" id="displaySchoolAddress">123 Education Lane, Learning City, Country</p>
            </div>

            <div class="mb-6 grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-2 text-gray-700">
                <div><span class="font-semibold">Student Name:</span> <span id="displayStudentName"></span></div>
                <div><span class="font-semibold">Father's Name:</span> <span id="displayFatherName"></span></div>
                <div><span class="font-semibold">Roll No:</span> <span id="displayRollNo"></span></div>
                <div><span class="font-semibold">Class:</span> <span id="displayClass"></span></div>
            </div>

            <h3 class="text-xl font-semibold text-gray-800 mb-4">Marks Details:</h3>
            <table class="w-full border-collapse mb-6">
                <thead>
                    <tr class="bg-gray-100 border-b border-gray-300">
                        <th class="py-2 px-4 text-left text-gray-600 font-semibold rounded-tl-lg">Subject</th>
                        <th class="py-2 px-4 text-left text-gray-600 font-semibold">Total Marks</th>
                        <th class="py-2 px-4 text-left text-gray-600 font-semibold rounded-tr-lg">Obtained Marks</th>
                    </tr>
                </thead>
                <tbody id="resultSubjectsTable">
                    <!-- Subject rows will be injected here -->
                </tbody>
            </table>

            <div class="bg-blue-50 p-5 rounded-lg shadow-sm grid grid-cols-1 md:grid-cols-2 gap-x-6 gap-y-2 text-gray-800 font-medium">
                <div><span class="font-bold">Grand Total Marks:</span> <span id="displayGrandTotal"></span></div>
                <div><span class="font-bold">Total Obtained Marks:</span> <span id="displayTotalObtained"></span></div>
                <div><span class="font-bold">Percentage:</span> <span id="displayPercentage"></span>%</div>
                <div><span class="font-bold">Grade:</span> <span id="displayGrade" class="text-blue-700"></span></div>
                <div class="col-span-1 md:col-span-2 text-center text-lg mt-3">
                    <span class="font-bold">Result Status:</span> <span id="displayResultStatus" class="font-extrabold text-green-700"></span>
                </div>
            </div>

            <div class="mt-8 text-sm text-gray-600">
                <p class="mb-2">Remarks: <span id="displayRemarks"></span></p>
                <p class="text-right mt-6">Date of Issue: <span id="displayIssueDate"></span></p>
            </div>

            <div class="flex justify-between mt-10 text-center text-gray-700">
                <div>
                    <hr class="border-t border-gray-400 mb-1 w-32 mx-auto">
                    <img id="displayClassTeacherSignature" src="" alt="Class Teacher Signature" class="mx-auto mt-2 signature-image object-contain" style="max-width: 120px; max-height: 60px;">
                    <p>Class Teacher Signature</p>
                </div>
                <div>
                    <hr class="border-t border-gray-400 mb-1 w-32 mx-auto">
                    <img id="displayPrincipalSignature" src="" alt="Principal Signature" class="mx-auto mt-2 signature-image object-contain" style="max-width: 120px; max-height: 60px;">
                    <p>Principal Signature</p>
                </div>
            </div>
        </div>

        <!-- Controls for Result Card (Print/New) -->
        <div id="resultControls" class="flex flex-col gap-4 mt-8 hidden">
            <div class="flex justify-center gap-4">
                <button id="printResultBtn" class="btn-secondary">Print Result Card</button>
                <button id="newResultBtn" class="btn-primary">Generate New Result</button>
            </div>
            
            <div id="sendEmailSection" class="bg-blue-100 p-6 rounded-xl shadow-inner mt-4">
                <h3 class="text-xl font-semibold text-gray-700 mb-4">Send Result via Email & WhatsApp</h3>
                <p class="text-sm text-gray-600 mb-4">
                    Email will be sent to the student's email found in your Google Sheet (matched by Name, Father's Name, Roll No, and Class).
                </p>
                <!-- studentEmailInput field removed as it's now fetched from sheet -->
                <button id="sendEmailBtn" class="btn-success w-full mb-2">Send Result Card via Email</button>
                <button id="generateWhatsappLinkBtn" class="btn-info w-full hidden">Generate WhatsApp Link</button>
                <p id="emailStatusMessage" class="text-sm text-center mt-2 hidden"></p>
            </div>
            <div id="whatsappSection" class="bg-green-100 p-6 rounded-xl shadow-inner hidden">
                <h3 class="text-xl font-semibold text-gray-700 mb-4">WhatsApp Link Generated</h3>
                <p class="text-sm text-gray-600 mb-4">Click the link below to open WhatsApp with the student's details.</p>
                <a id="whatsappLink" href="#" target="_blank" class="block text-center text-blue-700 hover:underline font-bold text-lg p-2 rounded-lg bg-green-200 hover:bg-green-300">Open WhatsApp Chat</a>
                <p id="whatsappStatusMessage" class="text-sm text-center mt-2 hidden text-red-600"></p>
            </div>
        </div>
    </div>

    <script>
        // REPLACE THIS WITH YOUR ACTUAL DEPLOYED GAS WEB APP URL!
        // This URL must be the 'Web app URL' obtained after deploying your Google Apps Script.
        const GOOGLE_APPS_SCRIPT_URL = 'https://script.google.com/macros/s/AKfycbxBQ5zdP5qEXZq_Hvljpph5FKlHkrqskoAeQtlomwZkH-BoQUR5Xb7sNY9OVmpWAgQ/exec'; 

        document.addEventListener('DOMContentLoaded', () => {
            // Get references to HTML elements
            const schoolNameInput = document.getElementById('schoolNameInput');
            const schoolAddressInput = document.getElementById('schoolAddressInput');
            const examTypeInput = document.getElementById('examTypeInput');
            const sessionInput = document.getElementById('sessionInput');
            const studentNameInput = document.getElementById('studentName');
            const fatherNameInput = document.getElementById('fatherName');
            const rollNoInput = document.getElementById('rollNo');
            const classInput = document.getElementById('class');
            const generateResultBtn = document.getElementById('generateResultBtn');
            const printResultBtn = document.getElementById('printResultBtn');
            const newResultBtn = document.getElementById('newResultBtn');
            const inputForm = document.getElementById('inputForm');
            const resultCardDisplay = document.getElementById('resultCardDisplay');
            const resultControls = document.getElementById('resultControls');
            const subjectsContainer = document.getElementById('subjectsContainer');

            // File Uploads
            const schoolLogoUpload = document.getElementById('schoolLogoUpload');
            const principalSignatureUpload = document.getElementById('principalSignatureUpload');
            const classTeacherSignatureUpload = document.getElementById('classTeacherSignatureUpload');
            const resultBackgroundUpload = document.getElementById('resultBackgroundUpload');
            const csvFileUpload = document.getElementById('csvFileUpload');
            const loadCsvBtn = document.getElementById('loadCsvBtn');

            // Display elements in the result card
            const displaySchoolLogo = document.getElementById('displaySchoolLogo');
            const displaySchoolName = document.getElementById('displaySchoolName');
            const displaySchoolAddress = document.getElementById('displaySchoolAddress');
            const displayExamType = document.getElementById('displayExamType');
            const displaySession = document.getElementById('displaySession');
            const displayPrincipalSignature = document.getElementById('displayPrincipalSignature');
            const displayClassTeacherSignature = document.getElementById('displayClassTeacherSignature');
            const displayStudentName = document.getElementById('displayStudentName');
            const displayFatherName = document.getElementById('displayFatherName');
            const displayRollNo = document.getElementById('displayRollNo');
            const displayClass = document.getElementById('displayClass');
            const resultSubjectsTable = document.getElementById('resultSubjectsTable');
            const displayGrandTotal = document.getElementById('displayGrandTotal');
            const displayTotalObtained = document.getElementById('displayTotalObtained');
            const displayPercentage = document.getElementById('displayPercentage');
            const displayGrade = document.getElementById('displayGrade');
            const displayResultStatus = document.getElementById('displayResultStatus');
            const displayRemarks = document.getElementById('displayRemarks');
            const displayIssueDate = document.getElementById('displayIssueDate');

            // Email/WhatsApp Sending Elements
            const sendEmailBtn = document.getElementById('sendEmailBtn');
            const generateWhatsappLinkBtn = document.getElementById('generateWhatsappLinkBtn');
            const emailStatusMessage = document.getElementById('emailStatusMessage');
            const whatsappSection = document.getElementById('whatsappSection');
            const whatsappLink = document.getElementById('whatsappLink');
            const whatsappStatusMessage = document.getElementById('whatsappStatusMessage');

            // Store Base64 strings for images (these will NOT be cleared on "New Result")
            let schoolLogoBase64 = "https://placehold.co/100x100/A0D468/ffffff?text=School+Logo"; // Default placeholder
            let principalSignatureBase64 = '';
            let resultCardBackgroundBase64 = '';

            // Store class-specific teacher signature data
            let classTeacherSignatures = {}; // Stores { 'Class Name': 'base64SignatureString' }

            // Define subjects and their default total marks and CSV header mapping
            const subjects = [
                { id: 'eng', name: 'English', csvHeader: 'English' },
                { id: 'math', name: 'Mathematics', csvHeader: 'Mathematics' },
                { id: 'sci', name: 'Science', csvHeader: 'Science' },
                { id: 'urdu', name: 'Urdu', csvHeader: 'Urdu' },
                { id: 'isl', name: 'Islamiyat', csvHeader: 'Islamiyat' },
                { id: 'arabic', name: 'Arabic', csvHeader: 'Arabic' },
                { id: 'computer', name: 'Computer', csvHeader: 'Computer' },
                { id: 'social_studies', name: 'Social Studies/Pak Studies', csvHeader: 'Social Studies' },
                { id: 'history', name: 'History', csvHeader: 'History' },
                { id: 'taleem_ul_quran', name: 'Taleem ul Quran', csvHeader: 'Taleem ul Quran' }
            ];

            // Function to add error highlight
            function addErrorHighlight(element) {
                element.classList.add('border-red-500', 'bg-red-50');
            }

            // Function to remove error highlight
            function removeErrorHighlight(element) {
                element.classList.remove('border-red-500', 'bg-red-50');
            }

            // Attach input/change listeners to remove highlights for required fields
            const requiredInputs = [
                schoolNameInput, schoolAddressInput, studentNameInput, fatherNameInput,
                rollNoInput, classInput, examTypeInput, sessionInput
            ];

            requiredInputs.forEach(input => {
                input.addEventListener('input', () => removeErrorHighlight(input));
                input.addEventListener('change', () => removeErrorHighlight(input)); // For select elements
            });


            // Function to handle image file uploads and convert to Base64
            function handleImageUpload(event, targetBase64Var) {
                const file = event.target.files[0];
                if (file) {
                    const reader = new FileReader();
                    reader.onload = (e) => {
                        const base64String = e.target.result;
                        if (targetBase64Var === 'schoolLogo') {
                            schoolLogoBase64 = base64String;
                        } else if (targetBase64Var === 'principalSignature') {
                            principalSignatureBase64 = base64String;
                        } else if (targetBase64Var === 'classTeacherSignature') {
                            const currentClass = classInput.value.trim();
                            if (currentClass) {
                                classTeacherSignatures[currentClass] = base64String;
                            } else {
                                alert('Please enter the Class first before uploading Class Teacher Signature.');
                                event.target.value = ''; // Clear file input
                                return;
                            }
                        } else if (targetBase64Var === 'resultBackground') {
                            resultCardBackgroundBase64 = base64String;
                        }
                    };
                    reader.readAsDataURL(file);
                } else {
                    // Reset variables if file is cleared
                    if (targetBase64Var === 'schoolLogo') {
                        schoolLogoBase64 = "https://placehold.co/100x100/A0D468/ffffff?text=School+Logo";
                    } else if (targetBase64Var === 'principalSignature') {
                        principalSignatureBase64 = '';
                    } else if (targetBase64Var === 'classTeacherSignature') {
                        const currentClass = classInput.value.trim();
                        if (currentClass && classTeacherSignatures[currentClass]) {
                            delete classTeacherSignatures[currentClass];
                        }
                    } else if (targetBase64Var === 'resultBackground') {
                        resultCardBackgroundBase64 = '';
                    }
                }
                // After upload/clear, immediately update the display for teacher signature
                updateClassTeacherSignatureDisplay();
            }

            // Function to update Class Teacher display based on current classInput value
            function updateClassTeacherSignatureDisplay() {
                const currentClass = classInput.value.trim();
                const teacherSignature = classTeacherSignatures[currentClass];

                if (teacherSignature) {
                    displayClassTeacherSignature.src = teacherSignature;
                    displayClassTeacherSignature.classList.remove('hidden');
                } else {
                    displayClassTeacherSignature.src = '';
                    displayClassTeacherSignature.classList.add('hidden');
                }
            }

            // Event listeners for image uploads
            schoolLogoUpload.addEventListener('change', (event) => handleImageUpload(event, 'schoolLogo'));
            principalSignatureUpload.addEventListener('change', (event) => handleImageUpload(event, 'principalSignature'));
            classTeacherSignatureUpload.addEventListener('change', (event) => handleImageUpload(event, 'classTeacherSignature'));
            resultBackgroundUpload.addEventListener('change', (event) => handleImageUpload(event, 'resultBackground'));

            // Event listener for class input change to update teacher signature
            classInput.addEventListener('input', updateClassTeacherSignatureDisplay);

            // Function to parse CSV data
            function parseCSV(csvString) {
                const lines = csvString.trim().split('\n');
                if (lines.length < 2) {
                    alert('CSV file must contain at least a header row and one data row.');
                    return null;
                }

                const headers = lines[0].split(',').map(header => header.trim());
                const dataRow = lines[1].split(',').map(data => data.trim());

                // Basic check for number of columns
                if (headers.length !== dataRow.length) {
                    alert('CSV header count does not match data column count in the first data row. Please check your CSV format.');
                    return null;
                }

                const result = {};
                headers.forEach((header, index) => {
                    result[header] = dataRow[index];
                });
                return result;
            }

            // Event listener for CSV file upload and data loading
            loadCsvBtn.addEventListener('click', () => {
                const file = csvFileUpload.files[0];
                if (!file) {
                    alert('Please select a CSV file to upload.');
                    return;
                }

                const reader = new FileReader();
                reader.onload = (e) => {
                    const csvData = e.target.result;
                    const parsedData = parseCSV(csvData);

                    if (parsedData) {
                        // Populate student information
                        schoolNameInput.value = parsedData['School Name'] || '';
                        schoolAddressInput.value = parsedData['School Address'] || '';
                        studentNameInput.value = parsedData['Student Name'] || '';
                        fatherNameInput.value = parsedData["Father's Name"] || '';
                        rollNoInput.value = parsedData['Roll No'] || '';
                        classInput.value = parsedData['Class'] || '';
                        examTypeInput.value = parsedData['Exam Type'] || examTypeInput.value; // Keep current if not in CSV
                        sessionInput.value = parsedData['Session'] || sessionInput.value; // Keep current if not in CSV


                        // Populate subject marks
                        subjects.forEach(subject => {
                            const obtainedInput = document.getElementById(subject.obtainedInputId);
                            const totalInput = document.getElementById(`totalMarks_${subject.id}`);
                            if (obtainedInput && totalInput && parsedData[subject.csvHeader]) {
                                const csvObtainedValue = parsedData[subject.csvHeader].trim();
                                if (csvObtainedValue !== '') { // Only set if not empty
                                    obtainedInput.value = csvObtainedValue;
                                } else {
                                    obtainedInput.value = ''; // Ensure it's clear if empty in CSV
                                }
                            } else {
                                obtainedInput.value = ''; // Clear if not found in CSV header
                            }
                            // Important: CSV currently only imports obtained marks. Total marks must be selected manually
                            // or added as a separate column in the CSV format if automation is needed.
                        });
                        alert('Data loaded successfully from CSV! Please verify total marks for each subject if needed.');
                        // After loading data, update teacher signature based on new class
                        updateClassTeacherSignatureDisplay();
                        // Also remove any previous error highlights
                        requiredInputs.forEach(input => removeErrorHighlight(input));
                    }
                };
                reader.readAsText(file);
            });

            // Function to calculate grade based on percentage
            function calculateGrade(percentage) {
                if (percentage >= 90) return 'A+';
                if (percentage >= 80) return 'A';
                if (percentage >= 70) return 'B';
                if (percentage >= 60) return 'C';
                if (percentage >= 50) return 'D';
                return 'F';
            }

            // Function to determine pass/fail status
            function getResultStatus(obtainedMarks, totalMarks, passingPercentage = 33) {
                const subjectPassingMarks = totalMarks * (passingPercentage / 100);
                if (obtainedMarks < subjectPassingMarks) {
                    return { status: 'Fail', color: 'text-red-600' };
                }
                return { status: 'Pass', color: 'text-green-700' };
            }

            // Function to generate the result card
            generateResultBtn.addEventListener('click', () => {
                console.log('Generate Result Card button clicked - Event Listener Fired!');
                let totalObtainedMarks = 0;
                let grandTotalMarks = 0;
                let isFailed = false;
                let remarksText = "Excellent performance!";
                let atLeastOneSubjectAdded = false;
                let validationPassed = true;

                // Validate main form fields (School & Student Info)
                requiredInputs.forEach(input => {
                    if (input.value.trim() === '') {
                        addErrorHighlight(input);
                        validationPassed = false;
                        console.log(`Validation failed for: ${input.id} (empty).`);
                    } else {
                        removeErrorHighlight(input);
                    }
                });

                if (!validationPassed) {
                    alert('Please fill in all required School & Student Information fields (highlighted in red).');
                    console.error('Required fields validation failed. Result card not generated.');
                    return;
                }
                console.log('Required fields validation passed.');


                // Clear previous subject rows in the result table
                resultSubjectsTable.innerHTML = '';

                // Iterate through subjects to collect marks and populate result table
                for (const subject of subjects) {
                    const subjectRowElement = document.querySelector(`[data-subject-id="${subject.id}"]`);
                    
                    if (!subjectRowElement) {
                        console.error(`Missing subject row element for ID: ${subject.id}. Check HTML data-subject-id attributes.`);
                        continue;
                    }

                    const obtainedMarksInput = subjectRowElement.querySelector(`input[id="obtainedMarks_${subject.id}"]`);
                    const totalMarksSelect = subjectRowElement.querySelector(`select[id="totalMarks_${subject.id}"]`);

                    if (!obtainedMarksInput || !totalMarksSelect) {
                        console.error(`Missing input or select element inside subject row for ${subject.name} (ID: ${subject.id}). Check HTML IDs.`);
                        continue;
                    }
                    
                    if (obtainedMarksInput.value.trim() !== '') {
                        const obtainedMarks = parseInt(obtainedMarksInput.value);
                        const totalMarks = parseInt(totalMarksSelect.value);

                        if (isNaN(obtainedMarks) || obtainedMarks < 0 || obtainedMarks > totalMarks) {
                            alert(`Please enter valid marks for ${subject.name}. Marks must be between 0 and ${totalMarks}.`);
                            isFailed = true;
                            remarksText = "Invalid marks entered for one or more subjects.";
                            console.error(`Subject marks validation failed for ${subject.name}. Result card not generated.`);
                            return;
                        }

                        totalObtainedMarks += obtainedMarks;
                        grandTotalMarks += totalMarks;
                        atLeastOneSubjectAdded = true;
                        
                        const subjectResult = getResultStatus(obtainedMarks, totalMarks);
                        if (subjectResult.status === 'Fail') {
                            isFailed = true;
                            if (remarksText === "Excellent performance!") remarksText = "Needs improvement in some subjects.";
                        }

                        const row = document.createElement('tr');
                        row.className = 'border-b border-gray-200 last:border-b-0';
                        row.innerHTML = `
                            <td class="py-2 px-4 text-gray-700">${subject.name}</td>
                            <td class="py-2 px-4 text-gray-700">${totalMarks}</td>
                            <td class="py-2 px-4 text-gray-700 ${subjectResult.color}">${obtainedMarks} ${subjectResult.status === 'Fail' ? '(Fail)' : ''}</td>
                        `;
                        resultSubjectsTable.appendChild(row);
                    } else {
                        console.log(`Subject: ${subject.name} - Skipped (empty obtained marks).`);
                    }
                }

                if (!atLeastOneSubjectAdded) {
                    alert('Please enter marks for at least one subject to generate the result card.');
                    console.error('No subjects added. Result card not generated.');
                    return;
                }
                console.log('At least one subject added. Proceeding with card generation.');

                if (remarksText === "Invalid marks entered for one or more subjects.") {
                    console.error('Invalid subject marks detected. Result card not generated.');
                    return;
                }

                // Overall result status and remarks logic
                if (isFailed) {
                    remarksText = "Student has failed in one or more subjects. Needs to work hard.";
                } else {
                    remarksText = "Excellent performance! Keep up the good work.";
                }

                const percentage = (totalObtainedMarks / grandTotalMarks * 100).toFixed(2);
                const grade = calculateGrade(percentage);
                const overallResultStatus = isFailed ? { status: 'FAIL', color: 'text-red-700' } : { status: 'PASS', color: 'text-green-700' };

                console.log(`Calculations: Total Obtained: ${totalObtainedMarks}, Grand Total: ${grandTotalMarks}, Percentage: ${percentage}, Grade: ${grade}, Result Status: ${overallResultStatus.status}`);

                // Update the result card display
                displaySchoolLogo.src = schoolLogoBase64;
                displaySchoolName.textContent = schoolNameInput.value.trim() || '';
                displaySchoolAddress.textContent = schoolAddressInput.value.trim() || '';
                displayExamType.textContent = examTypeInput.value + " Result";
                displaySession.textContent = "Session " + sessionInput.value;
                
                if (principalSignatureBase64) {
                    displayPrincipalSignature.src = principalSignatureBase64;
                    displayPrincipalSignature.classList.remove('hidden');
                } else {
                    displayPrincipalSignature.classList.add('hidden');
                }

                updateClassTeacherSignatureDisplay();

                if (resultCardBackgroundBase64) {
                    resultCardDisplay.style.backgroundImage = `url('${resultCardBackgroundBase64}')`;
                } else {
                    resultCardDisplay.style.backgroundImage = 'none';
                }

                displayStudentName.textContent = studentNameInput.value;
                displayFatherName.textContent = fatherNameInput.value;
                displayRollNo.textContent = rollNoInput.value;
                displayClass.textContent = classInput.value;
                displayGrandTotal.textContent = grandTotalMarks;
                displayTotalObtained.textContent = totalObtainedMarks;
                displayPercentage.textContent = percentage;
                displayGrade.textContent = grade;
                displayResultStatus.textContent = overallResultStatus.status;
                displayResultStatus.className = `font-extrabold ${overallResultStatus.color}`;
                displayRemarks.textContent = remarksText;
                displayIssueDate.textContent = new Date().toLocaleDateString('en-PK', { year: 'numeric', month: 'long', day: 'numeric' });

                // Show result card and controls, hide input form
                inputForm.classList.add('hidden');
                resultCardDisplay.classList.remove('hidden');
                resultControls.classList.remove('hidden');
                
                // Show email sending section after result is generated
                document.getElementById('sendEmailSection').classList.remove('hidden');
                document.getElementById('whatsappSection').classList.add('hidden'); // Hide WhatsApp link section initially
                console.log('Result card displayed successfully. Email/WhatsApp section is now visible.');
            });

            // Print button functionality
            printResultBtn.addEventListener('click', () => {
                window.print();
            });

            // New Result button functionality
            newResultBtn.addEventListener('click', () => {
                console.log('New Result button clicked. Resetting fields.');
                studentNameInput.value = '';
                fatherNameInput.value = '';
                rollNoInput.value = '';
                classInput.value = ''; // Clear class input to reset teacher signature display
                emailStatusMessage.classList.add('hidden'); // Hide email status message
                whatsappStatusMessage.classList.add('hidden'); // Hide WhatsApp status message

                subjects.forEach(subject => {
                    const obtainedInput = document.querySelector(`[data-subject-id="${subject.id}"] input[type="number"]`);
                    const totalInput = document.querySelector(`[data-subject-id="${subject.id}"] select`);
                    if (obtainedInput) {
                        obtainedInput.value = '';
                    }
                    if (totalInput) {
                        totalInput.value = '100'; // Reset total marks dropdowns to default 100
                    }
                });

                requiredInputs.forEach(input => removeErrorHighlight(input));

                resultCardDisplay.classList.add('hidden');
                resultControls.classList.add('hidden');
                inputForm.classList.remove('hidden');

                // Hide email/WhatsApp sending section when generating new result
                document.getElementById('sendEmailSection').classList.add('hidden');
                document.getElementById('whatsappSection').classList.add('hidden');
                
                updateClassTeacherSignatureDisplay();
                console.log('Fields reset. Input form visible.');
            });

            // Send Email button functionality
            sendEmailBtn.addEventListener('click', async () => {
                emailStatusMessage.classList.add('hidden'); // Hide previous status
                whatsappStatusMessage.classList.add('hidden'); // Hide previous status

                // Retrieve all necessary student details for GAS lookup
                const currentStudentName = studentNameInput.value.trim();
                const currentFatherName = fatherNameInput.value.trim();
                const currentRollNo = rollNoInput.value.trim();
                const currentClass = classInput.value.trim();
                
                // Validate required fields for GAS lookup
                if (!currentStudentName || !currentFatherName || !currentRollNo || !currentClass) {
                    alert('Student Name, Father\'s Name, Roll No, and Class are required for Google Sheet lookup to send email. Please ensure these fields are filled.');
                    return;
                }

                // Prepare data to send to Google Apps Script
                const payload = {
                    studentName: currentStudentName,
                    fatherName: currentFatherName,
                    rollNo: currentRollNo,
                    studentClass: currentClass,
                    resultCardHtml: document.getElementById('resultCardDisplay').innerHTML
                };

                // Validate GAS URL
                // Check if the URL is the placeholder string OR if it doesn't start with the generic GAS Web App prefix
                if (GOOGLE_APPS_SCRIPT_URL === 'YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE' || !GOOGLE_APPS_SCRIPT_URL.startsWith('https://script.google.com/macros/s/')) {
                    alert('Error: Google Apps Script Web App URL is not configured correctly. Please deploy your GAS and update the GOOGLE_APPS_SCRIPT_URL variable in the HTML code with the correct URL, ensuring it starts with "https://script.google.com/macros/s/".');
                    console.error('GOOGLE_APPS_SCRIPT_URL validation failed. Current URL:', GOOGLE_APPS_SCRIPT_URL);
                    return;
                }


                // Disable button and show loading message
                sendEmailBtn.disabled = true;
                sendEmailBtn.textContent = 'Sending Email...';
                generateWhatsappLinkBtn.disabled = true; // Disable WhatsApp button too
                emailStatusMessage.textContent = 'Sending email... Please wait. Looking up student in sheet.';
                emailStatusMessage.classList.remove('hidden', 'text-green-600', 'text-red-600');
                emailStatusMessage.classList.add('text-blue-600');

                try {
                    const response = await fetch(GOOGLE_APPS_SCRIPT_URL, {
                        method: 'POST',
                        mode: 'cors', // Use 'cors' mode for robust feedback
                        headers: {
                            'Content-Type': 'application/json',
                        },
                        body: JSON.stringify(payload),
                    });

                    if (!response.ok) {
                        const errorText = await response.text();
                        try {
                            const errorJson = JSON.parse(errorText);
                            throw new Error(`GAS Error: ${errorJson.message || errorText}`);
                        } catch (parseError) {
                            throw new Error(`HTTP error! status: ${response.status}, message: ${errorText}`);
                        }
                    }

                    const result = await response.json();
                    console.log('GAS response:', result);

                    if (result.success) {
                        emailStatusMessage.textContent = 'Result card sent successfully via email!';
                        emailStatusMessage.classList.remove('text-blue-600', 'text-red-600');
                        emailStatusMessage.classList.add('text-green-600');

                        if (result.whatsappNumber) {
                            generateWhatsappLinkBtn.classList.remove('hidden');
                            generateWhatsappLinkBtn.dataset.whatsappNumber = result.whatsappNumber;
                            generateWhatsappLinkBtn.dataset.studentName = currentStudentName;
                            generateWhatsappLinkBtn.dataset.examType = examTypeInput.value;
                            generateWhatsappLinkBtn.dataset.session = sessionInput.value;
                            generateWhatsappLinkBtn.disabled = false;
                            
                            whatsappStatusMessage.textContent = 'WhatsApp link ready!';
                            whatsappStatusMessage.classList.remove('hidden', 'text-red-600');
                            whatsappStatusMessage.classList.add('text-green-600');
                        } else {
                            generateWhatsappLinkBtn.classList.add('hidden');
                            whatsappStatusMessage.textContent = 'WhatsApp number not found in Google Sheet for this student.';
                            whatsappStatusMessage.classList.remove('hidden', 'text-green-600');
                            whatsappStatusMessage.classList.add('text-red-600');
                        }

                    } else {
                        emailStatusMessage.textContent = `Failed to send email: ${result.message}`;
                        emailStatusMessage.classList.remove('text-blue-600', 'text-green-600');
                        emailStatusMessage.classList.add('text-red-600');
                        generateWhatsappLinkBtn.classList.add('hidden');
                    }

                } catch (error) {
                    console.error('Error sending email request:', error);
                    let userFriendlyError = 'Failed to send email. Please check your internet connection and ensure the Google Apps Script URL is correct and deployed with "Anyone" access.';
                    if (error.message.includes("Failed to fetch")) {
                         userFriendlyError = 'Failed to connect to Google Apps Script. Please check your internet connection and ensure the GAS Web App URL is correct and active.';
                    } else if (error.message.includes("GAS Error:")) {
                         userFriendlyError = error.message;
                    }
                    emailStatusMessage.textContent = userFriendlyError;
                    emailStatusMessage.classList.remove('text-blue-600', 'text-green-600');
                    emailStatusMessage.classList.add('text-red-600');
                    generateWhatsappLinkBtn.classList.add('hidden');
                } finally {
                    sendEmailBtn.disabled = false;
                    sendEmailBtn.textContent = 'Send Result Card via Email';
                }
            });

            // Generate WhatsApp Link button functionality
            generateWhatsappLinkBtn.addEventListener('click', () => {
                const whatsappNum = generateWhatsappLinkBtn.dataset.whatsappNumber;
                const studentName = generateWhatsappLinkBtn.dataset.studentName;
                const examType = examTypeInput.value; // Get current values directly from input fields
                const session = sessionInput.value; // Get current values directly from input fields

                if (!whatsappNum) {
                    whatsappStatusMessage.textContent = 'WhatsApp number not available.';
                    whatsappStatusMessage.classList.remove('hidden');
                    return;
                }

                const message = encodeURIComponent(
                    `Assalam-o-Alaikum ${studentName},\n\n` +
                    `Aapka ${examType} ${session} ka result card tayyar hai. Aapko email bhi bhej di gayi hai.\n\n` +
                    `Shukriya,\nSchool Administration`
                );

                const whatsappUrl = `https://wa.me/${whatsappNum}?text=${message}`;
                whatsappLink.href = whatsappUrl;
                whatsappSection.classList.remove('hidden');
                whatsappStatusMessage.classList.add('hidden');
            });


            // Initial call to set up the teacher signature display on load
            updateClassTeacherSignatureDisplay();
            console.log('DOMContentLoaded: Initial setup complete.');
        });
    </script>
</body>
</html>
