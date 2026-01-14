# User Flows — Mudarris

**Product Type:** Educational SaaS (Islamic & Qur’anic schools)  
**Phase:** Planning & MVP Definition

This document outlines the **primary user flows** for Mudarris based on planning-phase assumptions. These flows describe how teachers, parents, and students interact with the system during normal usage.

---

## Flow 1: Teacher Logs a Daily Lesson

**Primary User:** Qur’an Teacher (Mudarris)

1. Teacher logs into Mudarris  
2. Selects a class or student  
3. Opens the daily lesson planner  
4. Records:
   - New memorization (Hifz)
   - Review (Murājaʿah)
   - Reading practice (Tilāwah)
   - Optional notes (e.g., tajwīd feedback)
5. Saves the lesson entry  

**Outcome:**
- Lesson is stored in the student’s history  
- Parent view is automatically updated  
- Student can view the lesson (if permitted)

---

## Flow 2: Parent Views Student Progress

**Primary User:** Parent / Guardian

1. Parent logs into Mudarris  
2. Selects their child’s profile  
3. Views:
   - Most recent lesson
   - Lesson history timeline
   - Teacher notes (read-only)
4. Exits without needing to message the teacher  

**Outcome:**
- Parent stays informed passively  
- Reduced manual communication for teachers  

---

## Flow 3: Student Reviews and Marks Lesson Complete (13+)

**Primary User:** Student (Age 13+)

1. Student logs in  
2. Views assigned lesson for the day  
3. Reviews highlighted āyāt (if assigned)  
4. Marks lesson as completed (if enabled)  

**Outcome:**
- Student gains clarity and accountability  
- Completion status is visible to teacher  

---

## Flow 4: Teacher Sends a Class Announcement

**Primary User:** Qur’an Teacher

1. Teacher opens class group  
2. Creates a text announcement  
3. Sends message to all linked parents (and students, if applicable)  

**Outcome:**
- Parents receive a single, consistent update  
- Teacher avoids repetitive individual messages  

---

## Flow 5: Teacher Reviews Lesson History

**Primary User:** Qur’an Teacher

1. Teacher selects a student  
2. Opens lesson history timeline  
3. Reviews previous memorization and reviews  
4. Adjusts upcoming lesson focus accordingly  

**Outcome:**
- Teaching decisions are informed by history  
- Reduced reliance on memory or external notes  

---

## Access Boundaries

- Teachers can create and edit lessons  
- Parents have read-only access to their child’s data  
- Students have limited self-view based on age and permissions  

These boundaries are designed to preserve trust and privacy.

---

## Flow Assumptions

- Teachers prefer minimal steps after each class  
- Parents primarily want visibility, not interaction  
- Students benefit from simple, non-gamified accountability  

All flows will be validated through feedback prior to development.

